# Vue-note

## 组件 （component）
### slot 内容分发
1. 子组件没有slot,父组件里的子组件标签里内容将被丢弃。
2. 具名slot（有name属性）,父组件会把片段插在子组件里对应name属性的slot里。有默认slot元素。

### 过渡效果
1. 过渡的css类名：.v-enter, .v-enter-active, .v-leave, .v-leave-active。过渡完就删除了。

