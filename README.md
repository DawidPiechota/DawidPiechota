```
console.log('%c✉ '+[...`🍔🍑🍧🍙🍔🍠🍙🍕🍓🍘🍟🍤🍑🎤🎢🌰🍗🍝🍑🍙🍜🐼🍓🍟🍝`].map(a=>String.fromCodePoint(a.charCodeAt(1)%123)).join(''),"font:2em system-ui;");
```

Old projects do not reflect my current coding practices :)
