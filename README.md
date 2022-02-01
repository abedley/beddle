# beddle

https://abedley.github.io/beddle/

##### Export

Copy results of `JSON.stringify(localStorage)`.

##### Import

```js
const data = JSON.parse(/*paste stringified JSON from clipboard*/);
Object.keys(data).forEach(k => {
  localStorage.setItem(k, data[k]);
});
```
