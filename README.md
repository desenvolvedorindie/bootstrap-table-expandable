# Bootstrap table expandable

Based on [jExpand](http://www.jankoatwarpspeed.com/expand-table-rows-with-jquery-jexpand-plugin/)

## Quick start

- [Download the latest release](https://github.com/wfcreations/bootstrap-table-expandable/archive/master.zip)
- Clone the repo: `https://github.com/wfcreations/bootstrap-table-expandable.git` 

```
<link href="css/bootstrap-table-expandable.css" rel="stylesheet">
    
<script src="js/bootstrap-table-expandable.js"></script>
```

## What's included

```
bootstrap-table-expandable/
├── css/
│   ├── bootstrap-table-expandable.css
├── example/
│   ├──img.png
│   ├──index.html
├── images/
│   ├──arrows.png
└── js/
│   ├── bootstrap-table-expandable.js
```

## Example

```
<table class="table table-expandable">
  <thead>
    <tr>
      <th>Country</th>
      <th>Population</th>
      <th>Area</th>
      <th>Official languages</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>United States of America</td>
      <td>306,939,000</td>
      <td>9,826,630 km2</td>
      <td>English</td>
    </tr>
    <tr>
      <td colspan="5">
        <!-- CONTENT -->  
      </td>
    </tr>
  </tbody>
</table>
```
### Result

![Example](https://raw.githubusercontent.com/wfcreations/bootstrap-table-expandable/master/example/img.png)
