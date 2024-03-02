# React components library

## Components

- NProgressBar

If you want to show a progress bar, when changing the route. In the component, had listener `a` tag click event, and show the progress bar and hide it after the route change.

But if you used api to change the route, you need to call `NProgressBar.start()` manually.

```tsx
function onChangingRoute() {
  NProgressBar.start()
  router.push('/new-route')
}
```

## Usage

```tsx
import { NProgressBar } from '@yjhtry/react-components'

function App() {
  return (
    <div>
      <NProgressBar />
    </div>
  )
}
```
