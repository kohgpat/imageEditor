# imageEditor.js
>A simple JavaScript image drag and drop, upload and cropping plugin.
## Main
```text
src/
├── imageEditor.css
├── imageEditor.js     
└── upload.svg
```
## Getting started
### Installation

Include files:

```html
<link  href="/path/to/imageEditor.css" rel="stylesheet">
<script src="/path/to/imageEditor.js"></script>
```
### Usage

#### Syntax

```js
new imageEditor(options)
```

- **options** (optional)
  - Type: `Object`
  - The options for imageEditor.

#### Example

```html
	<div class="imageEditor" id="imageEditor">
		<img class="imagePreview" id="imagePreview" src=""/>
		<input type="file" name="imageEditorInput" class="imageEditorInput" id="imageEditorInput" accept="image/*">
		<label for="imageEditorInput" class="imageEditorLabel" id="imageEditorLabel">
			<span class="editorLabelClick">Выберите изображение</span> или перетащите сюда
		</label>
	</div>
```
