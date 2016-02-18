# DataTables Filters Plugin
![Badge DataTables Filter v1.0](https://img.shields.io/badge/datatables.filters-v0.1-yellow.svg)

This [DataTables] plugin add a filter input on each DataTable columns.

![Screenshot](https://cloud.githubusercontent.com/assets/16703873/13138028/013df70a-d625-11e5-9cff-867e8fa42ef6.png)

## Example

``` javascript
$(document).ready(function() {

	// Initialize DataTable and active filter plugin
	$('#example').DataTable().filtersOn();

} );
```

## Evolutions

- Add the option to choose the type of input (text, select, range...)

   [DataTables]: <https://datatables.net/>
