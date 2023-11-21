

[How to Get URL Parameters with JavaScript](https://www.sitepoint.com/get-url-parameters-with-javascript/)


不同的叫法：

- URL parameters
- query string parameters
- URL variables

## 获取 URL 参数

使用 [URLSearchParams interface](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams) 来获取 URL 参数。

例如：

```
// https://example.com/?product=shirt&color=blue&newuser&size=m

const queryString = window.location.search;
console.log(queryString);
// ?product=shirt&color=blue&newuser&size=m

const urlParams = new URLSearchParams(queryString);

const product = urlParams.get('product')
console.log(product);
// shirt

const color = urlParams.get('color')
console.log(color);
// blue

const newUser = urlParams.get('newuser')
console.log(newUser);
// empty string
```


