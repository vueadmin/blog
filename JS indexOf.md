# JS indexOf

indexOf() 方法常用于查询数组中是否存在指定的元素

查询方向是从头到尾

如果查到对应元素，则返回元素首次查询到的索引

如果没有在数组中查询到指定元素，则返回 -1

indexOf 方法有2个参数

其中必填参数 item 为需要查询的指定元素

非必填参数 start 为开始检索的位置，start 为正整数

所有主要浏览器都支持 indexOf() 方法

但是 IE8 及 更早IE版本不支持该方法

```jsx
let arr = ['a', 'b', 'c', 'd', 'e', 'c' ];
console.log(arr.indexOf('c');); // 2
console.log(arr.indexOf('c', 3);); // 5
console.log(arr.indexOf('y');); // -1
```