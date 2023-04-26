## Ref

API Link: https://mock.apifox.cn/m1/2654642-0-default/progress

UI  Link: https://www.figma.com/file/ooPL0EEu9dw96uvxjAUBdp/%E6%9C%BA%E8%AF%95?node-id=0%3A1&t=pjY6bXgVGOShUtpb-1

参考的最终效果如`src/assets/Effect.mp4`所示

## 要求

* **禁止使用本项目没有的package**（除了和API请求相关的）
* 克隆或下载该项目到本地
* 根据UI的样式实现一个进度条的组件
* 让组件使用者可以设置进度的当前值、目标值和单位，其中当前值和目标值是必需的，单位是可选的（默认为空字符串）
* 把该组件注册为全局组件
* 在`src/App.vue`中放置3个所写的进度条组件，把它们三者的宽度分别设置为200px，400px和80vw
* 用`axios`写一个API以GET方法从上述Data URL中获取3个进度条需要的数据
* 增加两个点击按钮，功能分别是给第三个进度的进度增加10%和减少10%
* 当挂载组件和改变进度时，实现进度条从原始值（挂载时的原始值为0）到当前值增长（或减少）的动画效果
* 实现百分数的数字翻牌器动画
* 让组件使用者可以设置动画的延迟时间和持续时间（默认值都设置为0.5秒）
