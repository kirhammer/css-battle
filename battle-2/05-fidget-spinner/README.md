## Fidget Spinner

![Fidget Spinner](./fidget-spinner.pngg)

### HTML

```HTML
<div></div>
<style>
:root {
        --background-color: #09042a;
        --pink-color: #e78481;
        --skin-color: #f5bb9c;
        background: var(--background-color);
      }
      div {
        border-radius: 50%;
        height: 80px;
        left: 50%;
        background: var(--pink-color);
        position: absolute;
        transform: translate(-50%, -50%);
        top: 50%;
        width: 80px;
      }

      div::before {
        content: "";
        border-radius: 50%;
        box-shadow: 0 106px 0 0 var(--background-color),
          60px 53px 0 0 var(--pink-color), -60px 53px 0 0 var(--pink-color);
        height: 80px;
        left: 50%;
        background: var(--background-color);
        position: absolute;
        transform: translate(-50%, -93px);
        top: 50%;
        width: 80px;
      }

      div::after {
        content: "";
        border-radius: 50%;
        box-shadow: 0 106px 0 0 var(--skin-color),
          60px 53px 0 0 var(--background-color),
          -60px 53px 0 0 var(--background-color);
        height: 60px;
        left: 50%;
        background: var(--skin-color);
        position: absolute;
        transform: translate(-50%, -83px);
        top: 50%;
        width: 60px;
      }
</style>
```
