# SolidJS version of `react-markdown`

The implementation is 90% shamelessly copied from https://github.com/remarkjs/react-markdown.

Changes include:

- Replacing React specific component creation with SolidJS components
- Porting the implementation from javascript with JSDoc types to typescript

Please check the original repo for in-depth details on how to use.

## Installation

```
npm install solid-markdown
```

## Usage

```jsx
import SolidMarkdown from "solid-markdown";

const markdown = `
# This is a title

- here's
- a
- list
`;
const App = () => {
  return <SolidMarkdown children={markdown} />;
};
```

## TODO

- [ ] Port unit tests from from original library
