# safari下element ui表格错位问题

#### 其他浏览器没问题，只有Safari有问题，后来加上几行代码就解决了

```js
.el-table__body {
  width: 100%;
  table-layout: fixed !important;
}
```