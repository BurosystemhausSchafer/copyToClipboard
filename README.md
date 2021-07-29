# copyToClipboard
Simple Plugin to Copy the Content of an Container to the Clipboard with jQuery.


### Usage
```javascript
// Simple
$('#mydiv').copyToClipboard();

// With Option
$('#mydiv').copyToClipboard({
    buttonClass: "myCustomClass",
    buttonText: "Copy to xxx",
    themeClass: "myThemeClass",
    callback: function(copiedContent) {
        alert(copiedContent);
    }
});

```


### Releasenotes

##### Version 1.0.2 - 29.07.2021
- removed console.log() 

##### Version 1.0.1 - 29.07.2021
- Custom Themes and dark Theme
- Rework on Sample Page
- Fixed Bug with trim

##### Version 1.0.0 - 28.07.2021
- Release