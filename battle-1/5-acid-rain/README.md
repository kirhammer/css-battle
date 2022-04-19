## Acid Rain

![Acid Rain](./acid-rain.png)

### HTML

```HTML
<div></div>
<style>
    :root {
        --background-color: #0b2429;
        --drop-one-color: #f3ac3c;
        --drop-two-color: #998235;
        --drop-three-color: #f3ac3c;
        background: var(--background-color);
      }
    div {
        background: var(--drop-one-color);
        border-radius: 50%;
        height: 120px;
        left: 50%;
        position: absolute;
        top: 50%;
        transform: translate(0%, -100%);
        width: 120px;
      }

    div::before {
        background: var(--drop-three-color);
        border-radius: 50% 0 50% 50%;
        box-shadow: 60px -60px 0 0 var(--drop-two-color);
        content: "";
        height: 120px;
        position: absolute;
        transform: translate(-100%, 100%);
        width: 120px;
    }
</style>
```
