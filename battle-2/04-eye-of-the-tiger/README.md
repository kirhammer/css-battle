## Eye of the Tiger

![Eye of the Tiger](./eye-of-the-tiger.png)

### HTML

```HTML
<div></div>
<style>
      :root {
        --background-color: #0b2429;
        --eye-color: #998235;
        --pupil-color: #f3ac3c;
        background: var(--background-color);
      }

      div,
      div::before {
        left: 50%;
        position: absolute;
        top: 50%;
      }

      div {
        background: linear-gradient(
          45deg,
          var(--eye-color) 25%,
          var(--background-color) 25%,
          var(--background-color) 75%,
          var(--eye-color) 75%
        );
        height: 200px;
        transform: translate(-50%, -50%) rotate(45deg);
        width: 200px;
      }

      div::before {
        background: var(--background-color);
        border-radius: 50%;
        box-shadow: 0 0 0 45px var(--pupil-color),
          0 0 0 65px var(--background-color), 0 0 0 75px var(--eye-color);
        content: "";
        height: 50px;
        transform: translate(-50%, -50%);
        width: 50px;
      }
</style>
```
