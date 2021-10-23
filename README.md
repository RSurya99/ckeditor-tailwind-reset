# CKEditor Tailwind Reset

![example-ckeditor-tailwind-reset](/img/example.png)

For you all who use CKEditor with TailwindCSS maybe will get some errors that the style is looks no different. It was caused by Tailwind core plugin called `preflight`. 

With this `preflight` plugin, tailwind will reset all default browser styles. Meanwhile, CKEditor uses the default browser style for their WYSIWYG editor. That's why when you use both TailwindCSS and CKEditor you will not see any difference in the style.

In this repo, I have shared with you all, how to fix it. It's very simple, here's all steps you need to do:

- install using npm
```bash
npm i ckeditor-tailwind-reset
```

- import css files
```bash
@import 'ckeditor-tailwind-reset/ckeditor-tailwind-reset';
```

- run development

the styles will automatically compiled to your css files and boom, the style for CKEditor WYSISYG will be working now.