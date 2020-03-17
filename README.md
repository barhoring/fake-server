# fake-server

A tiny trivia 🤔 server.
Served with [My JSON Server](https://github.com/pandao/editor.md)

in dev tools or .js file

```
fetch('https://my-json-server.typicode.com/barhoring/fake-server/questions/1')
  .then(response => response.json())
  .then(json => console.log(json))
```

results to

```
    {
      "id": 1,
      "content": "Which two metals is pewter made from?",
      "options": [
        "Tin and lead",
        "Lead and coper",
        "Lead and gold",
        "Tin and gold"
      ]
    }
```

The first element in options is the correct answer, so shuffle options.
