Original : https://adgv.codeplex.com/

En

It`sa Windows Forms DataGridView Control with Excel-Like auto-filter context menu. Support Localization (currently RU, EN, FR)

EN

Windows Forms DataGridView control with Excel-like auto filter as a shortcut menu in column headers

While working on my project, I still could not find a suitable control for displaying tabular data with support for filtering and sorting. As a result, on the basis of ContextMenuStrip, an auto filter "as in Excel" was implemented.

adgv

Features:

Support for data types: All Numeric, DateTime, Boolean, all other types are interpreted as String
Sorting
Custom Filter
Filter based on selected values ​​from the TreeView element
The filter comes with a DataGridView that automatically adds an auto filter to its columns and processes filtering events. The only thing you need to do is add the BindingSource and process the FilterStringChanged and SortStringChanged events.

I spread the source code and the finished DLL "as is". If someone finds and corrects errors or offers better solutions I will be grateful. Unfortunately there is no time for further development and is not yet expected.
