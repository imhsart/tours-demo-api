# Tours API

A simple static tours API built using a JavaScript array of objects and hosted with GitHub Pages.

## Features

- 10 tour entries
- Random unique IDs
- Tour name
- Detailed description/info
- Tour image URLs
- Tour pricing

## Example Response

```json
{
  "id": "rec6d6T3q5EBIdCfD",
  "name": "Best of Paris in 7 Days Tour",
  "info": "Paris is one of the most iconic and romantic cities...",
  "image": "https://images.unsplash.com/photo-1502602898657-3e91760cbb34",
  "price": 1995
}
```

## Usage

Fetch the API data using JavaScript:

```js
fetch("https://imhsart.github.io/tours-demo-api/tours.json")
  .then((res) => res.json())
  .then((data) => console.log(data));
```


Feel free to use for learning and personal projects.
