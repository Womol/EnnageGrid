# EnnageGrid - interactive visible grid for your site.
This is a framework for creating an interactive visible grid for your site.

#### Installation:
- include the file "ennageGrid.min.js"
```html
	<script type="text/javascript" src="ennageGrid.min.js"></script>
```
- create canvas with id "ennageGrid"
```html
	<canvas id='ennageGrid'></canvas>
```
- initialize the object "ennageStart"

```JavaScript
var ennageStart = {
			duration: 2000,
			timing: 'arc',
			colRow: 3,
			color: 'black',
			width: '1'
		};
```
#### About the object
Animation time:
```JavaScript
var ennageStart = {
			duration: 2000
		};
```
Animation type (the property will be improved in the second version):
```
'arc', 'archery', 'line', 'quadratic', 'cubed', 'fivePow', 'elasticity'
```
```JavaScript
var ennageStart = {
			timing: 'arc'
		};
```
The number of columns and rows of Your table:
```JavaScript
var ennageStart = {
			colRow: 3
		};
```
Line color:
```JavaScript
var ennageStart = {
			color: 'black'
		};
```
Line width:
```JavaScript
var ennageStart = {
			width: '1'
		};
```