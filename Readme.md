<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/XtraPivotGrid_SaveLoadCollapsedState/Form1.cs) (VB: [Form1.vb](./VB/XtraPivotGrid_SaveLoadCollapsedState/Form1.vb))
<!-- default file list end -->
# How to save/load field values' collapsed states together with pivot grid's layout


<p>Field values' collapsed states can be restored only in the same layout they have been saved in. This example shows how to save and load a control's layout together with collapsed states to ensure that the states are loaded in the appropriate layout.</p><p>This example displays a pivot grid control and three buttons: Save, Load and Clear. When the Save button is clicked, the control layout and field values' collapsed states are saved to streams via the SaveLayoutToStream and SaveCollapsedStateToStream methods, respectively. On the Load button click, the RestoreLayoutFromStream method is firstly called to restore the layout, and then the collapsed states are loaded using the LoadCollapsedStateFromStream method. This ensures that even if you remove all fields from the pivot grid via the Clear button, the control's state will be restored when you click the Load button.</p>

<br/>

