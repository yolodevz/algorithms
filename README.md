### Helpers

##### find middle
```javascript
function findMiddle(high, low) {
    return Math.floor(low + (high - low) / 2)
}
```

### Type checking

negative zero

```javascript
function isItNegativeZero(x) {
    return x === 0 && (1 / x) === -Infinity;
}
```

NaN

```javascript
function isItNaN(x) {
    return x !== x;
}
```
