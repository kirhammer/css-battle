## Push Button

![Push Button](./push-button.png)

### HTML

```HTML
<div></div>
<style>
    :root {
        --background-color: #6592cf;
        --outer-circle-color: #243d83;
        --inner-circle-color: #eeb850;
        background: var(--background-color);
    }
    div {
        height: 150px;
        left: 50%;
        background: var(--outer-circle-color);
        position: absolute;
        transform: translate(-50%, -50%);
        top: 50%;
        width: 300px;
      }
    div::before {
        background: var(--inner-circle-color);
        border-radius: 50%;
        box-shadow: 0 0 0 50px var(--outer-circle-color),
          0 0 0 100px var(--background-color);
        content: "";
        height: 50px;
        position: absolute;
        transform: translate(125px, 50px);
        width: 50px;
    }
</style>
```
