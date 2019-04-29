# $.currencyFormatter

---

金额格式化

---

| 参数 | 数据类型 | 可选值 | 默认值 | 说明 |
| :--- | :--- | :--- | :--- | :--- |
| 0：number | number/string |  |  | 需要格式化的数字 |
| 1：precision | number |  | 0 | 精度即保留小数位数 |
| 2：prefix | string |  | '' | 前缀 |
| 3：suffix | string |  | '' | 后缀 |

#### 代码示例：

```js
$.currencyFormatter(10000);    // "10,000"

$.currencyFormatter(10000, 2);    // "10,000.00" 

$.currencyFormatter(10000, 2, '消费', '元');    // "消费10,000.00元"
```



