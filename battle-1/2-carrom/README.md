## Carrom

![Carrom](./carrom.png)

### HTML

```HTML
<div></div>
<style>
    :root {
        --background-color: #62374e;
        --square-color: #fdc57b;
        background-color: var(--background-color);
    }
      div {
        box-shadow: 250px 0 0 0 var(--square-color), 250px 150px 0 0 var(--square-color),
          0 150px 0 0 var(--square-color);
        background: var(--square-color);
        height: 50px;
        left: 50%;
        position: absolute;
        transform: translate(-150px, -100px);
        top: 50%;
        width: 50px;
    }
</style>
```
