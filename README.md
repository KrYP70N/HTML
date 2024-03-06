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


## Row and Column merging 

HTML tables can have cells that span over multiple rows and/or columns. In this case you need to merge row, column. 
You can use `<colspan>` and `<rowspan>` for this operation.

### Colspan

A cell span over multiple column. 

```
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
```

### Row

A cell span over multiple rows.

```
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
</tr>
</table>
```
