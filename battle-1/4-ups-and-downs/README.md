## Ups and Downs

![Ups and Downs](./ups-and-downs.png)

### HTML

```HTML
<div></div>
<style>
    :root {
        --background-color: #62306d;
        --wave-color: #f7ec7d;
        background: var(--background-color);
      }
    div {
        background: var(--wave-color);
        border-radius: 50% 50% 0 0;
        height: 100px;
        left: 50%;
        position: absolute;
        transform: translate(-50%, -100%);
        top: 50%;
        width: 100px;
      }

    div::before {
        background: var(--wave-color);
        border-radius: 0 0 50% 50%;
        box-shadow: 200px 0 0 0 var(--wave-color);
        content: "";
        height: 100px;
        left: 50%;
        position: absolute;
        transform: translate(-150%, 100%);
        width: 100px;
      }
</style>
```
