## Usage

```jsx
import { Swap } from "server-side-media-queries-for-react";

function App() {
  return (
    <Swap
      match={[
        ["(min-width: 800px)", <DesktopApp />],
        ["(min-width: 600px)", <TabletApp />],
        ["default", <MobileApp />],
      ]}
    />
  );
}

function DesktopApp() {
  return <h1>Desktop App</h1>;
}
function TabletApp() {
  return <h1>Tablet App</h1>;
}
function MobileApp() {
  return <h1>Mobile App</h1>;
}
```

## Related

[artsy/fresnel](https://github.com/artsy/fresnel/)
[ReactTraining/react-media](https://github.com/ReactTraining/react-media)
[contra/react-responsive](https://github.com/contra/react-responsive)

## License

MIT
