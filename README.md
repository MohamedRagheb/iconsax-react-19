<h1 align="center">iconsax for React  With react 19 support </h1>

<p align="center">
  <a href="https://iconsax-react.pages.dev/"><strong>Browse icons at site</strong></a>
</p>

> ©️ iconsax-react-19 [github](https://github.com/MohamedRagheb/iconsax-react-19) and
> [official website](https://iconsax-react.pages.dev/) (other format and platform available)

## Installation

### React

```bash
yarn add iconsax-react-19-update
# or
npm i iconsax-react-19-update

#or 
bun install iconsax-react-19-update
```

## Usage

```jsx
import React from 'react';
//import icon. for React Native import from 'iconsax-react-19-update-native'
import { EmojiHappy } from 'iconsax-react-19-update';

const Example = () => {
  // then use it as a normal React Component
  return <EmojiHappy />;
};
```

You can configure Icons with inline props:

```jsx
<EmojiHappy color="#eee" variant="Bulk" size={54} />
```

## Props

| Prop      | Type                                                | Default        | Note                   |
| --------- | --------------------------------------------------- | -------------- | ---------------------- |
| `color`   | `string`                                            | `currentColor` | css color              |
| `size`    | `number` `string`                                   | 24px           | size={24} or size="24" |
| `variant` | `Linear` `Outline` `TwoTone` `Bulk` `Broken` `Bold` | `Linear`       | icons styles           |


## License

[MIT](./LICENSE)
