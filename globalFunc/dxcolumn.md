## $.dxColumn

---

dxDataGrid单列格式化

| 参数 | 类型 | 可选值 | 默认值 | 描述 |
| :--- | :--- | :--- | :--- | :--- |
| 0:caption | String |  | 无 | 列名 |
| 1:dataField | String |  | 无 | 字段名 |
| 2:width | Number |  | 无 | 列宽 |
| 3:dataType | String | string/number/date/datetime/boolean/enum | String | 数据类型 |
| 4:extParams | Object/Enum |  | 无 | Object:列的补充配置参数，优先于前4个参数；Enum:当dataType="enum"时，xml文件生成的枚举对象。 |

```js
// 普通的格式化
$.dxColumn('姓名', 'name');

{
  caption: '姓名',
  dataField: 'name'
}
```



