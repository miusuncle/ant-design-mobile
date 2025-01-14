# Grid 栅格

<code src="./demos/index.tsx"></code>

## Grid

### 属性

| 属性    | 说明           | 类型                                                       | 默认值 |
| ------- | -------------- | ---------------------------------------------------------- | ------ |
| columns | 列数           | `number`                                                   | -      |
| gap     | 格子之间的间距 | `number \| string \| [number \| string, number \| string]` | `0`    |

### CSS 变量

| 属性             | 说明               | 默认值       | 全局变量 |
| ---------------- | ------------------ | ------------ | -------- |
| --gap            | 间距大小           | `0`          | -        |
| --gap-vertical   | 垂直方向的间距大小 | `var(--gap)` | -        |
| --gap-horizontal | 水平方向的间距大小 | `var(--gap)` | -        |

## Grid.Item

### 属性

| 属性    | 说明     | 类型                                                            | 默认值 |
| ------- | -------- | --------------------------------------------------------------- | ------ |
| span    | 跨度     | `number`                                                        | `1`    |
| onClick | 点击事件 | `(event: React.MouseEvent<HTMLDivElement, MouseEvent>) => void` | -      |
