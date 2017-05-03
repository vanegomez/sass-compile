## Compile SASS without Rails

1. Create project folder and file style.scss

```
  mkdir sass-tutorial
  touch style.scss
```
2. Add some styling to style.scss

```scss
  body {
    background-color: #eee;
    color: #800;

    p {
      color: #800;
    }
  }
```
3. To compile and create a .css file in order to see the css output, from your terminal run:  
```
  sass style.scss style.css
```
