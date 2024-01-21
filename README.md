## Getting Started

First install the dependencies:

```bash
npm i
```

Then, run the server:

```bash
npm run server
```

Create your andpoint in db.json. Here is an example:

```JSON
{
	"your_andpoint_name": []
}
```

Yoy can add more andpoints in db.json and use them in your app.

## How to use

```TypeScript
axios.get('http://localhost:3333/your_andpoint_name')
axios.post('http://localhost:3333/your_andpoint_name', data)
```

If you want to clear the json before your post request you can use this post request:

```TypeScript
axios.post('http://localhost:3333/reset', { your_andpoint_name: [] })
```
