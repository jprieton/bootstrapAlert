Bootstrap Alerts v1.2.0
===========

A jQuery plugin for displaying Bootstrap alerts. [Demo](http://jprieton.github.io/bootstrap-alerts)

Usage
---

```javascript
$('#alert-container').bootstrapAlert({
    type: 'success', // Optional, , default: 'info',  values: 'success', 'info', 'warning' or 'danger'
    dismissible: true, // Optional, default: true 
    heading: 'My Heading', // Optional, default: ''
    message: 'My message.',  // Required,
    clear: true // Optional, Clears the container, default: true 
});
```

License
---

Licensed under the [MIT License](http://opensource.org/licenses/mit-license.html)
