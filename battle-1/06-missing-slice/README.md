## Missing Slice

![Missing Slice](./missing-slice.png)

### HTML

```HTML
<div></div>
<style>
    :root {
        --background-color: #e3516e;
        --slice-1-color: #f7f3d7;
        --slice-2-color: #51b5a9;
        --slice-3-color: #fade8b;
        background: var(--background-color);
      }
    div {
        background-image: conic-gradient(
          from 180deg,
          var(--slice-1-color) 90deg,
          var(--slice-2-color) 90deg,
          var(--slice-2-color) 180deg,
          var(--slice-3-color) 180deg,
          var(--slice-3-color) 270deg,
          var(--background-color) 270deg
        );
        border-radius: 50%;
        height: 200px;
        left: 50%;
        position: absolute;
        top: 50%;
        transform: translate(-50%, -50%);
        width: 200px;
    }
</style>
```
