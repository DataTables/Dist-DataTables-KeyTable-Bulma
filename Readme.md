# KeyTable for DataTables with styling for [Bulma](https://bulma.io/)

This is the distribution package for the [KeyTable extension](https://datatables.net/extensions/keytable) for [DataTables](https://datatables.net/) with styling for [Bulma](https://bulma.io/).

KeyTable allows you to use keyboard navigation on a DataTables enhanced table, like an Excel spreadsheet - a cell shows a focus outline which can be moved using the keyboard or mouse operations. This can be particularly useful in an editable table that uses Editor allowing end users to update data very quickly.


## Installation

### Browser

To use DataTables with a simple `<script>` tag, rather than using this package, it is recommended that you use the [DataTables download builder](//datatables.net/download) which can create CDN or locally hosted packages for you, will all dependencies satisfied.

### npm

For installation via npm, yarn and other similar package managers, install this package with your package manager - e.g.:

```
npm install datatables.net-bm
npm install datatables.net-keytable-bm
```

Then, to load and initialise the software in your code use:

```
import DataTable from 'datatables.net-bm';
import 'datatables.net-keytable-bm'

new DataTable('#myTable', {
    // initialisation options
});
```


## Documentation

Full documentation and examples for KeyTable can be found [on the DataTables website](https://datatables.net/extensions/keytable).


## Bug / Support

Support for DataTables is available through the [DataTables forums](//datatables.net/forums) and [commercial support options](//datatables.net/support) are available.

### Contributing

If you are thinking of contributing code to DataTables, first of all, thank you! All fixes, patches and enhancements to DataTables are very warmly welcomed. This repository is a distribution repo, so patches and issues sent to this repo will not be accepted. Instead, please direct pull requests to the [DataTables/KeyTable](http://github.com/DataTables/KeyTable). For issues / bugs, please direct your questions to the [DataTables forums](//datatables.net/forums).


## License

This software is released under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.

