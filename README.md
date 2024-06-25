
# Local Integration DTU Learn
1. [Link](https://learn.inside.dtu.dk/d2l/le/content/187635/Home)
2. Script
```javascript
var oldElement = document.getElementById('d2l_two_panel_selector_main');
if (oldElement) {
    var newElement = document.createElement('iframe');
    newElement.src = 'http://localhost:3000/';
    newElement.width = '100%';
    newElement.height = '900px';

    oldElement.parentNode.replaceChild(newElement, oldElement);
    console.log('Element replaced successfully.');
} else {
    console.log('Element with ID d2l_two_panel_selector_main not found.');
}
const element = document.getElementsByClassName('d2l-navigation-s-group-text')[1]
element.textContent = 'Feedbot'
```
