---
path: "/props"
date: "2017-11-07"
title: "Props"
---

| Props                  | Type   | Default     | Description                                                                                 |
|------------------------|--------|-------------|---------------------------------------------------------------------------------------------|
| **Component props** ||||
| values                 | array  | []          | Selected values                                                                             |
| options                | array  | []          | Available options                                                                           |
| keepOpen               | bool   | false       | If true, dropdown will always stay open (good for debugging)                                |
| dropdownGap            | number | 5           | Gap between select element and dropdown                                                     |
| multi                  | bool   | false        | If true - will act as multi-select, if false - only one option will be selected at the time |
| placeholder            | string | "Select..." | Placeholder shown where there are no selected values                                        |
| addPlaceholder         | string | "+"         | Secondary placeholder on search field if any value selected                                 |
| disabled               | bool   | false       | Disable select and all interactions                                                         |
| style                  | object | {}          | style object to pass to sselect                                                             |
| className              | string |             | CSS class attribute to pass to sselect                                                      |
| loading                | bool   | false       | loading indicator                                                                           |
| clearable              | bool   | true        | Clear all indicator                                                                         |
| separator              | bool   | true        | Separator line between close all and dropdown handle                                        |
| dropdownHandle         | bool   | true        | dropdown handle to open/close dropdown                                                      |
| searchBy               | string | label       | search by object property in values                                                         |
| closeOnScroll          | bool   | false       | If true, scrolling the page will close the dropdown                                         |
| **Callback props** ||||
| onChange               | func   |             | On values change callback, returns array of values objects |
| onDropdownClose        | func   |             | fires upon dropdown close                                                                   |
| onDropdownOpen         | func   |             | fires upon dropdown open                                                                    |
| onClearAll             | func   |             | fires upon clearing all values (via custom renderers)                                       |
| onSelectAll            | func   |             | fires upon selecting all values (via custom renderers)                                      |
| [contentRenderer](/prop/content-renderer)        | func   |             | Overrides internal content component (the contents of the select component)                |
| [itemRenderer](/prop/item-renderer)           | func   |             | Overrides internal item in a dropdown                                                       |
| [noDataRenderer](/prop/no-data-renderer)         | func   |             | Overrides internal "no data" (shown where search has no results)                            |
| [optionRenderer](/prop/option-renderer)         | func   |             | Overrides internal option (the pillow with an "x") on the select content                    |
| [inputRenderer](/prop/input-renderer)          | func   |             | Overrides internal input text                                                               |
| [loadingRenderer](/prop/loading-renderer)        | func   |             | Overrides internal loading                                                                  |
| [clearRenderer](/prop/clear-renderer)          | func   |             | Overrides internal clear button                                                             |
| [separatorRenderer](/prop/separator-renderer)      | func   |             | Overrides internal separator                                                                |
| [dropdownRenderer](/prop/dropdown-renderer)       | func   |             | Overrides internal dropdown component                                                       |
| [dropdownHandleRenderer](/prop/dropdown-handle-renderer) | func   |             | Overrides internal dropdown handle                                                          |