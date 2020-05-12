## CSS3 animation（动画） 属性

| 属性名称 | 属性说明 |
| :-------- | :-------------------------------------------------------------------------------- |
| animation-duration | 	动画指定需要多少秒或毫秒完成 |
| animation-timing-function| 	设置动画将如何完成一个周期|
| animation-delay| 	设置动画在启动前的延迟间隔。|
| animation-iteration-count| 	定义动画的播放次数。|
| animation-direction| 	指定是否应该轮流反向播放动画。|
| animation-fill-mode	| 规定当动画不播放时（当动画完成时，或当动画有一个延迟未开始播放时），要应用到元素的样式。|
| animation-play-state| 	指定动画是否正在运行或已暂停。|


linear	动画从头到尾的速度是相同的。	测试
ease	默认。动画以低速开始，然后加快，在结束前变慢。	测试
ease-in	动画以低速开始。	测试
ease-out	动画以低速结束。	测试
ease-in-out	动画以低速开始和结束。	测试
cubic-bezier(n,n,n,n)	在 cubic-bezier 函数中自己的值。可能的值是从 0 到 1 的数值。	