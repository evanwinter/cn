# @evanwinter/cn

Utility function for merging Tailwind class names as popularized by @shadcn/ui.

### Installation

```bash
npm i @evanwinter/cn
```

### Usage

```tsx
import { cn } from '@evanwinter/cn';

export function Button({ className, ...props }: React.ButtonHTMLAttributes<HTMLButtonElement>) {
  return (
    <button {...props} className={cn("bg-black text-white rounded", props.className)}>
  )
}
```
