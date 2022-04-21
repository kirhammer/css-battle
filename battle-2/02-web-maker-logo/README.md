## Web Maker Logo

![Web Maker Logo](./web-maker-logo.png)

### HTML

```HTML
<div></div>
<style>
      :root {
        --background-color: #f2f2b6;
        --strong-orange-color: #fd4602;
        --soft-orage-color: #ff6d00;
        background: var(--background-color);
      }
      div {
        position: absolute;
        left: 50%;
        top: 50%;
      }

      div::before,
      div::after {
        content: "";
        border-left: 75px solid transparent;
        border-right: 75px solid transparent;
        position: absolute;
      }

      div::before {
        border-top: 130px solid var(--soft-orage-color);
        transform: translate(-140px, -65px);
        filter: drop-shadow(20px 0 0 var(--strong-orange-color));
      }

      div::after {
        border-bottom: 130px solid var(--strong-orange-color);
        transform: translate(-30px, -65px);
        filter: drop-shadow(20px 0 0 var(--soft-orage-color));
      }
</style>
```
