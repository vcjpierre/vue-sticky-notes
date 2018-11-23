# Sticky Docs

Sticky To-Do Notes is a `Vue.js` Plugin you can embed in your project. so it requires:

*   [Vue.js](https://vuejs.org/)
*   [http-vue-loader](https://github.com/FranckFreiburger/http-vue-loader)
*   [Fontawesome.css](https://fontawesome.com/)
*   [Bootstrap.css](https://getbootstrap.com/docs/3.3/)  
    \- You can customize the style anyway

### Plugin Content

Once downloaded, unzip the compressed folder to see the structure of (the compiled) Sticky To-Do Notes. You'll see something like this:

``` bash
Sticky Notes/
	└── plugin/
		├── components/
		│   ├── multiNotes.vue
		│   ├── sharedNote.vue
		│   └── singleNote.vue
		├── css/
		│   └── stickyNotes.css
		├── js/
		│   └── stickyNotes.js
		└── fonts/
			├── Poppins-Light.ttf
			├── Poppins-Medium.ttf
			├── Poppins-Regular.ttf
			├── Poppins-SemiBold.ttf
			├── toriom-light.ttf
			└── toriom-medium.ttf
```            
				
### How To Embed In My Project

Just use the tag `<sticky-notes>` inside a div with `id="notes"` and `class="notes"`
``` html
<div id="notes" class="notes">
  <div class="container">
   <sticky-notes></sticky-notes>
  </div>
</div>
```	

### For Shared Note !

To make your note sharable you need to create HTML page called `shared.html` and use `<shared-note>` tag as following :
``` html
<div id="notes" class="notes">
  <div class="container">
   <shared-note></shared-note>
  </div>
</div>
```