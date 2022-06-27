# ljw2487.github.io

1. <a src="https://www.runoob.com/jsref/jsref-map.html">JavaScript Array map() 方法 | 菜鸟教程</a>

```js
array.map(function(currentValue,index,arr), thisValue)
	// 方法返回一个新数组，数组中的元素为原始数组元素调用函数处理后的值。
	// 方法按照原始数组元素顺序依次处理元素。
	// map() 不会对空数组进行检测
	// map() 不会改变原始数组
===示例===  返回一个数组，数组中元素为原始数组的平方根
var numbers = [4, 9, 16, 25];
function myFunction() {
    x = document.getElementById("demo")
    x.innerHTML = numbers.map(Math.sqrt);
};  // 2,3,4,5
```
