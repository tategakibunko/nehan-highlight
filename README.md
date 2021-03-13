# nehan-highlight

[nehan](https://github.com/tategakibunko/nehan) plugin for code highlight.

## create nehan style

```typescript
import * as HighlightStyle from 'nehan-highlight';

const style = HighlightStyle.create({
  selector: "pre>code"
});
```

## use markup

```html
<pre><code class="lang-typescript">
const x: string = "foo";
</code></pre>
```
