---
order: 0
title: 基本用法
---

警告提示，展现需要关注的信息，适用于简短的警告提示。

## en-US


```js
import { Tooltip,Space } from '@oc/design';

const App = () => {
  return (
      <Space>
        {
            ['left','leftTop','leftBottom','right','rightTop','rightBottom','top','topLeft','topRight','bottom','bottomLeft','bottomRight'].map(_=> <Tooltip key={_} placement={_} content="This is tooltip content">
              <span>{_}</span>
            </Tooltip>)
        }
      </Space>
  )
}

export default App
```
