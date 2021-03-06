react-native-beautiful-image
===

The Image component that supports fadeIn animation and shows placeholderSource if the main source can't be loaded. More will be implemented.

![Sample](screenshot.gif)

## Installation

```bash
npm i --save react-native-beautiful-image
```

Please file an issue if you have any trouble!


## Usage

```jsx
import Image from 'react-native-beautiful-image';

....

<Image source={{ uri: 'https://avatars2.githubusercontent.com/u/1784243?v=3&s=460' }}
    placeholderSource={require('./placeholder.png'} />
```
## Options
Supports all [Image](https://facebook.github.io/react-native/docs/images.html) properties.

option | Info
------ | ----
placeholderSource | Show `placeholderSource` if the `source` can't be loaded.

## Todo
- Support more animations
- Lazy Loading based on position in View.
- TBD

## License

MIT
