# TABLE

`Table` allow developer to arrange data into `row` and `column`.
Table encompasses with these tag :

| Tag Name      | Description |
| ------------- | ----------- |
| `<table>`     | root tag for table         |
| `<tr>`        | table row                  |
| `<td>`        | table cell                 |
| `<thead>`     | header content for table   |
| `<tbody>`     | body content for table     |
| `<tfoot>`     | footer content for table   |
| `<th>`        | table header cell          |
| `<caption>`   | table caption              |
| `<colgroup>`  | a group of one or more columns in a table for formatting |
| `<col>`       | specifies column properties for each column within a `<colgroup>` element |


#### Example

```
<table>
  <caption>Monthly Sales Data</caption>
  <colgroup>
    <col style="background-color: yellow;">
    <col style="background-color: cyan;">
  </colgroup>
  <thead>
    <tr>
      <th>Month</th>
      <th>Sales</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>January</td>
      <td>$10,000</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$12,000</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td>$22,000</td>
    </tr>
  </tfoot>
</table>
```

