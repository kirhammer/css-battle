## Leafy Trail

![Leafy Trail](./leafy-trail.png)

### HTML

```HTML
<div></div>
 <style>
    :root {
        --background-color: #0b2429;
        --leaf-1-color: #f3ac3c;
        --leaf-2-color: #998235;
        --leaf-3-color: #1a4341;
        background: var(--background-color);
      }
    div {
        box-shadow: -50px 0 0 0 var(--leaf-2-color),
          -100px 0 0 0 var(--leaf-3-color);
        position: absolute;
        top: 50%;
        left: 50%;
        width: 150px;
        height: 150px;
        background: var(--leaf-1-color);
        border-radius: 66.67% 0;
        transform: translate(-16.67%, -50%);
    }
</style>
```
