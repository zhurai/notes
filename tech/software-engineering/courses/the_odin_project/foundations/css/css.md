# CSS Notes
## Selectors
- Class Selector: **.**
  - ``.player``
- ID Selector: **#**
  - ``#title``

## Properties
- multiple ``font-family`` is for failsafe purposes
- ``font-weight`` (0-1000, or bold)
  - 700 = bold
- images ``width`` and ``height``
  - can use ``auto`` keyword on height and declare width to keep proportions/aspect ratio 
  - ideally you should explictly state the height and width

## Cascade
determines which rules get applied to the HTML
### Specificity
- more specific >  less specific
- inline styles has highest specificity
- ID selector > Class selector > Type selector > Universal selector
- more selectors (e.g. ``.main .list``) > less selectors (e.g. ``.subsection``
  - (less priority than id/class/type selector method)
- Only cancels out conflicting declarations, non conflicting declarations will still apply no matter the priority/cascade/specificity
### Inheritance
- parents apply CSS properties to descendents
- lower priority (gets overriden) by descendents own CSS properties
### Inheritance
## Rule Order
- last defined gets applied

## HTML 
- External
  - in <head>
  - <link rel="stylesheet" href="file.css">
- Internal
  - <style></style>
- Inline
  - <tag style="">
  - does not use selectors


