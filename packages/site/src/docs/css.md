## CSS

`css` takes in styles and returns a class name. It is the foundation of emotion.

```jsx
import { css } from 'emotion'

const flex = css`
  display: flex;
`
const justifyCenter = css`
  ${flex};
  justifyContent: center;
`

<div className={justifyCenter}>
 Centered Content
</div>
```