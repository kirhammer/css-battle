## Forking Crazy

![Forking Crazy](./forking-crazy.png)

### HTML

```HTML
<div></div>
 <style>
    :root {
      --background-color: #6592cf;
      --fork-color: #060f55;
      background: var(--background-color);
    }
    div {
      width: 20px;
      height: 110px;
      background: var(--background-color);
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -91%);
      border-radius: 70px;
      box-shadow: 40px 0 0 0 var(--background-color),
        -40px 0 0 0 var(--background-color), 0 150px 0 0 var(--fork-color),
        20px 0 0 0 var(--fork-color), 60px 0 0 0 var(--fork-color),
        -20px 0 0 0 var(--fork-color), -60px 0 0 0 var(--fork-color),
        0 -90px 0 60px var(--background-color),
        0 30px 0 60px var(--fork-color);
    }
</style>
```
