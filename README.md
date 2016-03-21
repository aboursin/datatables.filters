# DataTables Filters Plugin
![Badge DataTables Filter v1.0](https://img.shields.io/badge/datatables.filters-v0.1-yellow.svg)

This [DataTables] plugin add a filter input on each DataTable columns.

![Screenshot](https://cloud.githubusercontent.com/assets/16703873/13925720/b0e7391e-ef89-11e5-9565-8dd8669d7f99.png)

## Example

``` javascript
$(document).ready(function() {

	// Initialize DataTable and active filter plugin
	$('#example').DataTable().filtersOn();

} );
```

### Available options

**Searchable**

The following line set a non-searchable column : no filter input will be displayed.

`"columnDefs" : [{"targets": [2], "searchable": false}]`

**Type of search input**

The following line set a 'select' search input : instead of the standard input text, a select with options will be displayed.

`"columnDefs" : [{"targets": [2], "searchtype": "select"}]`

## Evolutions

- Add the following type of input : [gt, gte, eq, lte, lt][value]

   [DataTables]: <https://datatables.net/>
