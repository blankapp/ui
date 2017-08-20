---
title: RadioButton
---
Single selection controls

## 示例

```jsx
<RadioButton.Group>
  <RadioButton text={'Option1'} checked={true} />
  <RadioButton text={'Option2'} />
</RadioButton.Group>
```

## API

### 属性
名称 | 描述 | 类型 | 可选值 | 默认值
--- | --- | --- | --- | ---
`CircleComponent` | - | element | - | -
`text` | 显示的文本 | string | - | 空字符串 ('')
`value` | - | string | - | -
`checked` | 是否处于选中状态 | bool | - | `false`

### 事件
名称 | 描述
--- | ---
`onCheckedChange` | -
