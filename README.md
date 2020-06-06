# ExtendScriptModules
Adobe ExtendScript modules.  

# Installation
Clone or download this repositry.  
If you download, I recommend putting this repositry in your home folder.

# Usage
You can import these modules using the preprocessor directives, for example:
```javascript
//@include "~/ExtendScriptModules/common/array_filter.jsxinc"
```

You can also use `//@includepath` 
(It's useful when importing multiple modules.) :

```javascript
//@includepath "common; SUI; InDesign;"
//@include "array_filter.jsxinc"
//@include "json2.jsxinc"
//@include "exportTextFile.jsxinc"
//@include "multiButtonSUIDialog.jsxinc"
```

For more details about preprocessor directives, see 'JAVASCRIPT TOOLS GUIDE'.

If you want to import all script modules, import 'AllModules.jsxinc'.
```javascript
//@include "~/ExtendScriptModules/AllModules.jsxinc"
```

# notice
## license
see [LICENSE](LICENSE).

## the same name function
**Do not use a function with the same name as modules in any scope.**  
It can cause serious malfunctions.

## about common modules
Modules in common folder are tested in InDesign and Illustrator.  
If you use any common module in other apps, test it carefully.

