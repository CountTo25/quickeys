# Quickey

### Its probably useless and done better

I just wanted to make in-house hotkey plugin for quick rollout

### How to use

```
var hotkeys = new Quickeys();
hotkeys.register(['Shift','Space'], doStuff);
hotkeys.register(['Shift', 'S'], doStuff, true); //third argument: boolean, true = prevent default event

function doStuff() {
    console.log('yay');
}
```

There are probably better plugins that do that. Also, check the [demo](https://countto25.github.io/quickeys/) and its [source](https://github.com/CountTo25/quickeys/blob/main/index.html)
