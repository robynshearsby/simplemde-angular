# SimpleMDE for AngularJS

### Installation
```bash
bower install simplemde-angular --save
```
```html
<script src="simplemde-angular/dist/simplemde-angular.js"></script>
```
```javascript
app = angular.module('app', ['simplemde'])
```

### Usage
```html
<textarea simplemde='{spellChecker: false}'></textarea>
```

```html
<textarea simplemde='options'></textarea>
```

```html
<textarea simplemde ng-model='text'></textarea>
```

### Contributing

`git clone https://github.com/hansottowirtz/simplemde-angular.git`<br/>
`cd simplemde-angular`<br/>
`npm install`<br/>
`gulp build`