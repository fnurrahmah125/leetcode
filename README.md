# LeetCode - JS

## Easy

### 2667. Create Hello World Function
```javascript
var createHelloWorld = function() {
    
  return function(...args) {
    return "Hello World"
  };
};

const f = createHelloWorld();
f(); // 👉 "Hello World"
```

### 2620. Counter
```javascript
var createCounter = function(n) {
  var currentValue = n
    return function() {
      const current = currentValue
      currentValue++
      return current
    };
};

const counter = createCounter(10)
counter() // 👉 10
counter() // 👉 11
counter() // 👉 12
```

## Medium
