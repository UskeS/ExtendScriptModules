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
//@includepath "~/ExtendScriptModules/"
//@include "common/array_filter.jsxinc"
//@include "common/json2.jsxinc"
//@include "common/exportTextFile.jsxinc"
//@include "SUI/multiButtonSUIDialog.jsxinc"
```

For more details about preprocessor directives, see 'JAVASCRIPT TOOLS GUIDE'.

# notice
## license
see [LICENSE](LICENSE).

## about common modules
Modules in common folder are testd in InDesign and Illustrator.  
If you use these in other apps, test it carefully.

