# 匹配多个连续字符串


```javascript
/([a-zA-Z])\1/
```

关键在于`()`以及`\1`.

* 正则中匹配数字是`\d`d并不是准确的数字
* 要是想匹配正确的数字，必须使用`[]`

所以`\1`是对`([a-zA-Z])`的引用。可是**为什么能够实现连续字符串**。只要我们把上面那句话写清楚就能够明白，首先`\1=([a-zA-Z])`，所以**/([a-zA-Z])\1/** 就是 **/([a-zA-Z])([a-zA-Z])/**

* 和直接`/([a-zA-Z])([a-zA-Z])/`无法匹配到连续的区别在于，因为这样可以`kz`
* 后者是前置的引用，代表两个相同的字符串

**链接**

* [例子](https://blog.csdn.net/heyue_99/article/details/68927621)