# beddle

https://abedley.github.io/beddle/

##### Export

On the OG site, copy results of `JSON.stringify(localStorage)`.

##### Import

On this site:

```js
const data = JSON.parse(/*paste stringified JSON from clipboard*/);
Object.keys(data).forEach(k => {
  localStorage.setItem(k, data[k]);
});
```
