## Eye of Sauron

![Eye of Sauron](/battle1/eye-of-sauron.png)

### HTML
```HTML
<div></div>
<style>
    :root {
        --background-color: #191210;
        --eye-color: #eca03d;
        --pupil-color: #84271c;
        background: var(--background-color);
    }

    div {
        background: var(--eye-color);
        border-radius: 70px 70px 0 0;
        height: 50px;
        left: 50%;
        position: absolute;
        top: 50%;
        transform: translate(50%, -100%);
        width: 100px;
    }

    div::before {
        background: var(--eye-color);
        border-radius: 0 0 70px 70px;
        content: "";
        height: 50px;
        position: absolute;
        transform: translate(-200px, 50px);
        width: 100px;
      }

    div::after {
        background: var(--pupil-color);
        border-radius: 50%;
        box-shadow: 0 0 0 25px var(--background-color),
          0 0 0 45px var(--eye-color), -100px 0 0 5px var(--background-color),
          100px 0 0 5px var(--background-color);
        content: "";
        height: 50px;
        position: absolute;
        transform: translate(-75px, 25px);
        width: 50px;
    }
</style>
```