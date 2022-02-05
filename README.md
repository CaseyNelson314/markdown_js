# markdown_js

markdownファイルにJavaScriptを埋め込む実験


```js script  
import './demo-wc-card.js';  
import { html } from 'lit-html';  
```  

# This is my component  

```js story  
export const demo = () => html`  
<demo-wc-card header="HEADER"></demo-wc-card>  
`;  
```
export const demo = () => html`  
<demo-wc-card header="HEADER"></demo-wc-card>  
`;  
