## Try it

[https://my-json-server.typicode.com/typicode/demo](https://my-json-server.typicode.com/typicode/demo)

## Use your own data

Used json-generator to generate db.json

https://json-generator.com/

[
  '{{repeat(0, 200)}}',
  {
    userId: '{{integer(1, 10)}}',
    id: '{{index()}}',
    title: '{{lorem(1, "sentences ")}}',
    content: '{{lorem(2, "sentences ")}}'
  }
]