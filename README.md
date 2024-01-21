## Getting Started

First, run the server:

```bash
npm run server
```

## Create with:

```bash
npm i json-server
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
