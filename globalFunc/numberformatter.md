# $.numberFormatter

---

数字格式化

---

| 参数 | 类型 | 可选值 | 默认值 | 说明 |
| :--- | :--- | :--- | :--- | :--- |
| 0：number | number/string |  |  | 需要格式化的数据，如1000   1,000.00 |
| 1：precision | number |  |  | 精度 |
| 2：prefix | string |  | '' | 前缀 |
| 3：suffix | string |  | '' | 后缀 |

#### 代码示例：

```js
$.numberFormatter('1,000.00');    // "1000"

$.numberFormatter(1000, 2);    // "1000.00"

$.numberFormatter(10.12, 4, '', '%');    // "10.1200%"
```



