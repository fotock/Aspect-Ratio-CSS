## Aspect Ratio CSS

```html
<style>
  .ratio-1-1,.ratio-2-1,.ratio-3-2,.ratio-4-3,.ratio-3-4,.ratio-16-9 {position:relative;overflow:hidden;}
  .ratio-1-1:before,.ratio-2-1:before,.ratio-3-2:before,.ratio-4-3:before,.ratio-3-4:before,.ratio-16-9:before {display:block;content:"";width:100%;}
  .ratio-1-1>.content,.ratio-2-1>.content,.ratio-3-2>.content,.ratio-4-3>.content,.ratio-3-4>.content,.ratio-16-9>.content {position: absolute;top:0;left:0;right:0;bottom:0;}
  .ratio-1-1:before {padding-top:100%;}
  .ratio-2-1:before {padding-top:50%;}
  .ratio-3-2:before {padding-top:66.67%;}
  .ratio-4-3:before {padding-top:75%;}
  .ratio-3-4:before {padding-top:133.33%;}
  .ratio-16-9:before {padding-top:56.25%;}
</style>

<body>
  <div class="ratio-3-2">
    <div class="content">
      Hello, world
    </div>
  </div>
</body>
```
