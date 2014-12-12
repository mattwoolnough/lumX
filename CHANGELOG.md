# Changelog

## v0.2.12:

#### New fetures:
 - text-fields: fixing padding
 - text-fields: add textarea in text fields components

#### Bug fixes:
 - dropdown: stop click propagation
 - dialog: stop click propagation


## v0.2.11:

#### New fetures:
 - selects: converter model=>items & vice versa

#### Bug fixes:
 - selects: selected items init in the dropdown
 - selects: indexof between objects
 - selects: pointers between model & selected

#### Breaking changes:
 - selects "selected" is replaced by "model"


## v0.2.10:

#### Bug fixes:
 - text-fields: replace "name" by "field-name"


## v0.2.9:

#### Bug fixes:
 - text-fields: manage the html name parameter


## v0.2.8:

#### Bug fixes:
 - data-table: cell padding
 - scrollbar: use angular $window selector
 - search filter: reset model on clear
 - select: fix filter width

#### Breaking changes:
 - the text-field directive is totally changed


## v0.2.7:

#### New fetures:
 - search filter: add width and position attrs

#### Bug fixes:
 - search filter: use filter-width parameter


## v0.2.6:

#### New fetures:
 - tabs: tabs can have a shadow
 - tabs: remove padding on .tabs__panes
 - dialogs: add responsive behaviour for dialogs

#### Bug fixes:
 - text-field: move the label when init with a value
 - search-field: display the cleaning cross when reopening the field
 - data-table: fix cells paddings and add responsive behaviour
 - ripple: disable animation once finished


## v0.2.5:

#### Bug fixes:
 - tabs: use ng-if for hiding/showing tabs


## v0.2.4:

#### Bug fixes:
 - data table: rounded style for primary image


## v0.2.3:

#### Bug fixes:
 - scrollbar: use angular selecter instead of jQuery $
 - scrollbar: Add Scrollbar Service


## v0.2.2:

#### New fetures:
 - tabs: add links background color
 - tabs: custom colors for tabs
 - tabs: icons in tabs links
 - typography: replace headings by typography
 - data-table: add component
 - z-depth: add z-depth classes
 - headings: add sass vars and classes

#### Bug fixes:
 - search filter: pointer cursor on search icon


## v0.2.1:

#### New fetures:
 - colors: rename black and white classes


## v0.2.0:

#### New fetures:
 - search-filter: add model management
 - select: remove delete button from multiple tag
 - select: deselection on non-multiple selects
 - select: add hover delete for selected items in multiple
 - select: update demo
 - select: add loader and helpers
 - select: link filter to callback
 - fab: left and right direction for fab

#### Bug fixes:
 - dropdown: add focus on search filter
 - tabs: panes padding
 - toolbar: floating elements in left/right areas
 - fab: wrong animation with left direction
 - select: null pointer on filter if none selected
 - select: disable text selection on tag


## v0.1.15:

#### Bug fixes:
 - notification: missing method from injector object


## v0.1.14:

#### New fetures:
 - tabs: change default theme and parameter name
 - tabs: add scope variables and dark/light theme
 - tabs: add color themes
 - colors: add theme global colors and colors classes
 - text-fields: add default values for parameters
 - text-fields: dynamic value management for fixed label and valid state
 - text-fields: fixed label and valid input state

#### Bug fixes:
 - select: change width attribute
 - notification: remove circular dependency between $compile & ui-router
 - file-input: remove "change" in directive binding
 - file-input: fix jshint error
 - file-input: fix "change" parameter binding


## v0.1.13:

#### Bug fixes:
 - file-input: long filenames displayed on one line
 - search-filter: stop propagation with multiple search in the same page


## v0.1.12:

#### New fetures:
 - search-filter: better click handlers
 - search-filter: ergonomic improvements
 - search-filter: create search filter component

#### Bug fixes:
 - file-input: Fix indentation to the Allman style
 - file-input: remove transclude
 - toolbars: label margin and clearfix


## v0.1.11:

#### Bug fixes:
 - fab: action buttons position


## 0.1.10:

#### Bug fixes:
 - toolbars: fix toolbar label line height


## v0.1.9:

#### Bug fixes:
 - toolbars: padding according to buttons size


## v0.1.8:

#### New fetures:
 - toolbars: add toolbar component

#### Bug fixes:
 - buttons: change default sizes
 - buttons: increase font size for icon buttons


## v0.1.7:

#### New fetures:
 - colors: add new colors to default settings
 - colors: Material design color palette with Sass


## v0.1.6:
*No major changes.*


## v0.1.5:
*No major changes.*


## v0.1.4:

#### New fetures:
 - progress: create service to manage progress
 - progress: enhance existing circular progress

#### Bug fixes:
 - select: remove unselect method on elements
 - ripple: disable pointer events


## v0.1.3:
*No major changes.*


## v0.1.2:

#### Bug fixes:
 - switch: Manage fast rate for click
 - checkbox: Manage fast rate for click


## v0.1.1:

#### Bug fixes:
 - ripple: set z-index to put ripple under link