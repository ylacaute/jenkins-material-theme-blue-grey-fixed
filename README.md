
See https://github.com/afonsof/jenkins-material-theme/issues/191

Original file: https://cdn.rawgit.com/afonsof/jenkins-material-theme/gh-pages/dist/material-blue-grey.css

Changes: remove the `!important` in the code below in order to keep mono space in console :

```css
#main-panel > pre {
    font-family: Roboto Mono,monospace !important;
}
:not(div.ace_editor) {
    font-family: Roboto,sans-serif !important;
    outline: 0;
}
```


