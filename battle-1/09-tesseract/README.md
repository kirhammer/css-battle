## Tesseract

![Tesseract](./tesseract.png)

### HTML

```HTML
<div></div>
 <style>
  body {
    --background-color: #222730;
    --square-color: #4caab3;
    --center-color: #393e46;
    margin: 0;
    background: var(--background-color);
  }
  div {
    background: var(--square-color);
    height: 150px;
    left: 50%;
    position: absolute;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
  }
  div::before {
    background: var(--square-color);
    box-shadow: 0 0 0 50px var(--background-color);
    content: "";
    height: 150px;
    left: 50%;
    position: absolute;
    top: 50%;
    transform: translate(-50%, -50%) rotate(45deg);
    width: 150px;
  }

  div::after {
    background: var(--center-color);
    border-radius: 50%;
    content: "";
    height: 50px;
    left: 50%;
    position: absolute;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 50px;
  }
</style>
```
