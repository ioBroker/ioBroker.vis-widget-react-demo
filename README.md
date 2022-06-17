## visAttrs notation:

### Example: 
```
visAttrs: [
    {
        name: 'groupName',
        fields: [
            {
                name: 'fieldName',
                type: 'id',
            }
        ]
    }
]
```

### group properties:
* name: group name
* indexFrom: for indexed group, start number (if number) or name of field with start number
* indexTo: for indexed group, end number (if number) or name of field with end number
* fields

### field properties:
#### common
* name: field name
* type: field type
* default: default value
* onChangeFunc: name of function if field changes
* indexFrom: for indexed field, start number (if number) or name of field with start number
* indexTo: for indexed field, end number (if number) or name of field with end number
#### id type
* filter: filter
#### select, nselect, auto types
* options: array of options (strings)
#### number, slider types
* min: min value
* max: max value
* step: step
#### style type
* filterFile
* filterName
* filterAttrs
* removeName

