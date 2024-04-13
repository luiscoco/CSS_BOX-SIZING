# CSS: BOX-SIZING

See this youtube video: https://www.youtube.com/watch?v=Vx854s9YE78

See also this web pages: 

**HTML**: https://developer.mozilla.org/es/docs/Web/HTML

**CSS**: https://developer.mozilla.org/en-US/docs/Learn/CSS

**JavaScript**: https://developer.mozilla.org/en-US/docs/Learn/JavaScript

Playground: https://developer.mozilla.org/en-US/play

![image](https://github.com/luiscoco/CSS_BOX-SIZING/assets/32194879/19c9a839-9f9d-497f-8dd7-cc7ffba35159)

For debugging the web page we select the **More Tools->Developer Tools**

Then we selec the **Elements** tab

![image](https://github.com/luiscoco/CSS_BOX-SIZING/assets/32194879/46c929c9-d145-4603-8f16-3951a0e4efda)

**HTML**

```html
<div class="box"></div>
```

**CSS**

```css
.box {
  width: 250px;
  height: 250px;
  background: #09f;
  border: 10px solid blue;
  padding: 100px;

  box-sizing: content-box;
}
```

![image](https://github.com/luiscoco/CSS_BOX-SIZING/assets/32194879/08ae06e4-0a19-43a5-bc80-128836eea432)

**HTML**

```html
<div class="box"></div>
```

**CSS**

```css
.box {
  width: 250px;
  height: 250px;
  background: #09f;
  border: 10px solid blue;
  padding: 100px;

  box-sizing: border-box;
}
```

![image](https://github.com/luiscoco/CSS_BOX-SIZING/assets/32194879/ea7b6b6e-0dcc-45f7-909b-054f56b9dd5b)


