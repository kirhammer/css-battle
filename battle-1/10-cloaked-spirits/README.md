## Cloaked Spirits

![Cloaked Spirits](./cloaked-spirits.png)

### HTML

```HTML
<div></div>
<style>
   :root {
        --background-color: #62306D;
        --cloak-color: #F7EC7D;
        --circle-color-one: #AA445F;
        --circle-color-two: #E38F66;
        background: var(--background-color);
      }
      div {
        background: var(--cloak-color);
        box-shadow: -100px 100px 0 0 var(--cloak-color), 100px 100px 0 0 var(--cloak-color);
        height: 100%;
        left: 50%;
        position: absolute;
        top: 33.33%;
        transform: translateX(-50%);
        width: 100px;
      }

      div::before {
        background: var(--circle-color-two);
        border-radius: 50%;
        box-shadow: -100px 100px 0 0 var(--circle-color-one), 100px 100px 0 0 var(--circle-color-one);
        content: "";
        height: 100px;
        position: absolute;
        transform: translateY(-50px);
        width: 100px;
      }

      div::after {
        background: var(--circle-color-one);
        border-radius: 50%;
        box-shadow: -100px 100px 0 0 var(--circle-color-two), 100px 100px 0 0 var(--circle-color-two);
        content: "";
        height: 60px;
        position: absolute;
        transform: translate(20px, -30px);
        width: 60px;
      }
</style>
```
