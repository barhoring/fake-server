# fake-server
My JSON Server experiment

in dev tools or .js file

```
fetch('https://my-json-server.typicode.com/barhoring/fake-server/posts/1')
  .then(response => response.json())
  .then(json => console.log(json))
```

results to
```
0: Object { id: 1, firstName: "Bar" }
​
1: Object { id: 2, lastName: "Horing" }
​
2: Object { id: 3, lastName: "Amir" }
```
