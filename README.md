# fps-meter

Fast and simple FPS meter for React. Renders to a canvas element and uses requestAnimationFrame to update the FPS counter.

![](https://share.cleanshot.com/y7S2FbpP/download)

### Install

```sh
yarn add @schickling/fps-meter
```

### Usage

```tsx
import React from 'react'
import { FPSMeter } from '@schickling/fps-meter'

export const MyApp: React.FC = () => {
  return (
    <div>
      <FPSMeter className="absolute right-0 top-0" height={40} />
    </div>
  )
}
```
