# VisualzieMeD3

## About the Project

Here we add some information.

## HTML Code

At this point we try to embed `HTML` code into the MarkDown file.

```html preview-story
<my-card>
  <h2>Hello world!</h2>
  <button>Click me!</button>
</my-card>
```

## Java Script

At this point we try to embed `JavaScript` code into the MarkDown file.

<my-el></my-el>

```js script
import { LitElement, html } from 'https://unpkg.com/lit-element?module';

class MyEl extends LitElement {
  render() {
    this.innerHTML = '<p style="color: red">I am alive</p>';
  }
}

customElements.define('my-el', MyEl);
```
