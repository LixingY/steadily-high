# RegExp 最佳实践

### 1. 整数

```js
/^-?[0-9]\d*$/
```

### 2. 正整数

```js
/^[1-9]\d*$/
```

### 3. 正数

```js
/^[+]{0,1}(\d+)$|^[+]{0,1}(\d+\.\d+)$/
```

### 4. 0-1 之间的数字

```js
/^(0(\.\d+)?|1)$/
```

### 5. 只允许输入字母、-、数字

```js
/^[a-zA-Z0-9-]{0,}$/
```

### 6. 手机号

```js
/^1[3|4|5|6|7|8|9][0-9]\d{8}$/
```

