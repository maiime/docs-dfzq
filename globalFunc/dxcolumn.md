## $.dxColumn

---

dxDataGrid单列格式化

---

| 参数 | 类型 | 可选值 | 默认值 | 描述 |
| :--- | :--- | :--- | :--- | :--- |
| 0:caption | String |  | 无 | 列名 |
| 1:dataField | String |  | 无 | 字段名 |
| 2:width | Number |  | 无 | 列宽 |
| 3:ext | String/object |  | 无 | 拓展参数 |

```js
// 一般
$.dxColumn('姓名', 'name');

// 带有宽度
$.dxColumn('姓名', 'name', 180);

// 日期 date
$.dxColumn('姓名', 'name', 180, 'date');

// 时间 datetime
$.dxColumn('姓名', 'name', 180, 'datetime');

// 枚举 TypeEmnu是枚举文件内已定义的枚举对象
$.dxColumn('类型', 'type', 180, TypeEmun);

// 布尔 boolean
$.dxColumn('姓名', 'name', 180, 'boolean');

// 货币 currency 
$.dxColumn('价格', 'price', 180, 'currency');    // 1000 => 1,000
$.dxColumn('价格', 'price', 180, 'currency,2');    // 1000 => 1,000.00
$.dxColumn('价格', 'price', 180, 'currency,2,￥');    // 1000 => ￥1,000.00
$.dxColumn('价格', 'price', 180, 'currency,2,￥,万元');    // 1000 => ￥1,000.00万元

// 数字 number
$.dxColumn('数量', 'count', 180, 'number');    // 10 => 10
$.dxColumn('价格', 'price', 180, 'number,2');    // 10 => 10.00
$.dxColumn('价格', 'price', 180, 'number,2,总计');    // 1000 => 总计1000
$.dxColumn('百分比', 'percent', 180, 'number,2,,%');    // 10 => 10.00%

// 自定义
$.dxColumn('价格', 'price', 180, {
    // dx column config
});
```



