##Aspect Ratio CSS

####Demo

https://fotock.github.io/Aspect-Ratio-CSS

 

####CSS

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

####LICENSE
MIT License

Copyright (c) 2016 Shelley Shyan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
