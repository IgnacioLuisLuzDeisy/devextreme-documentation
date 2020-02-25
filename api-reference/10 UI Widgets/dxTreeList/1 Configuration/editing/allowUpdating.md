---
default: false
type: Boolean | function(options)
---
---
##### shortDescription
Specifies whether a user can update rows. It is called for each data row when defined as a function

##### param(options): Object
Information about the current row.

##### field(options.component): dxTreeList
The widget's instance.

##### field(options.row): dxTreeListRowObject
The row's properties.

##### return: Boolean
**true** if the row can be updated; otherwise **false**.

---
See an example in the [allowAdding](/api-reference/10%20UI%20Widgets/dxTreeList/1%20Configuration/editing/allowAdding.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/editing/#allowAdding') option.

#####See Also#####
- [onRowUpdating](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/onRowUpdating.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/#onRowUpdating')
- [onRowUpdated](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/onRowUpdated.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/#onRowUpdated')
- [cellValue(rowIndex, visibleColumnIndex, value)](/api-reference/10%20UI%20Widgets/GridBase/3%20Methods/cellValue(rowIndex_visibleColumnIndex_value).md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Methods/#cellValuerowIndex_visibleColumnIndex_value')