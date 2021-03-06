## Wiggly Moustache

![Wiggly Moustache](./wiggly-moustache.png)

### HTML

```HTML
<div></div>
 <style>
      :root {
        --background-color: #f5d6b4;
        --moustache-color: #d86f45;
        background: var(--background-color);
      }

      div {
        background: var(--moustache-color);
        border-radius: 50px 50px 0 0;
        height: 50px;
        left: 50%;
        position: absolute;
        transform: translate(-50px, -50px);
        top: 50%;
        width: 100px;
      }

      div::before {
        background: var(--moustache-color);
        border-radius: 0 0 50px 50px;
        box-shadow: 160px 0 0 0 var(--moustache-color);
        content: "";
        height: 50px;
        position: absolute;
        transform: translate(-80px, 50px);
        width: 100px;
      }

      div::after {
        background: #f5d6b4;
        border-radius: 50%;
        box-shadow: -80px 0 0 0 var(--background-color), 80px 0 0 0 var(--background-color),
          -120px 0 0 -20px var(--moustache-color), 120px 0 0 -20px var(--moustache-color);
        content: "";
        height: 60px;
        position: absolute;
        transform: translate(20px, 20px);
        width: 60px;
      }
</style>
```
