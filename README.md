# Bootstrap Tags Input
Bootstrap Tags Input is a jQuery plugin providing a Twitter Bootstrap user interface for managing tags.


## Usage
var objectArr = [name: "someData", name: "someData2"];

var blood = new Bloodhound({
  datumTokenizer: Bloodhound.tokenizers.obj.whitespace('name'),
  queryTokenizer: Bloodhound.tokenizers.whitespace,
  local: contactBookComposite
});

$('#id').tagsinput({
  itemValue: 'name',
  itemText: 'name',
  typeaheadjs: {
    name: 'input.name',
    displayKey: 'name',
    valueKey: 'name',
    source: blood.ttAdapter()
  }
});

## Features
* Objects as tags
* True multi value
* Typeahead
* Modified for Bootstrap 4 Alpha

## Unmantained code AS-IS
If you need this plugin please fork and continue development, as I only needed it for a single project and will not continue further maintenance :)
