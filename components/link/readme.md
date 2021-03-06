# Link

The link is a very simple component that acts mostly as a wrapper for the HTML anchor. It's not included in Material Design Specification but we provide it as an easy way to create links with icons and counters. Let's see an example:

<!-- example -->
```jsx
import Link from 'react-toolbox/lib/link';

const LinksTest = () => (
  <nav>
    <Link href="/#/components/link" label="Work" count={4} icon='business' />
    <Link href="/#/components/link" label="Blog" icon='speaker_notes' />
    <Link href="/#/components/link" label="Explore" icon='explore' />
  </nav>
);
```

## Properties

You can add as many properties as you want to be directly transferred to the output anchor element. Apart from them you have the following properties:

| Name              | Type          | Default         | Description|
|:-----|:-----|:-----|:-----|
| `label`       | `String`        |         | The text string used for the text content of the link.|
| `className`     | `String`      | `''`            | Sets a custom class name to add styles to the link.|
| `count`         | `Number`        |                 | Sets a count number useful to display in the page how many times was visited for example.|
| `icon`          | `String`        |                 | An icon key string to include a `FontIcon` component in front of the text.|

