---
order: 0
title: 基本用法
---

警告提示，展现需要关注的信息，适用于简短的警告提示。

```js
import { Popover, Button } from "@oc/design";

function App() {
  const [visible, setVisible] = React.useState(false);
  return (
    <Popover
      content={
        <span>
          <p>Here is the text content</p>
          <p>Here is the text content</p>
        </span>
      }
    >
      <div type="primary">Click</div>
    </Popover>
  );
}

export default App;
```
