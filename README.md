<h1>Hi there!</h1>

<h3>Who am I?</h3> 

```js
const app = require("express").Router()

app.get("/info", async (req, res, next) =>{
	try {
		const sendInfo = {
			"Nickname": "Marel",
			"Languages": ["NodeJS", "TypeScript", "ReactJS", "HTML", "CSS", "Python"]
			"Description": "I'm Loris, and I work as a MERN Stack developer.\n
			Started years ago with some C++ I then abandoned coding.\n
			I started another time ain 2020 thanks to Strive School."
		};
		res.status(200).send(sendInfo);
	} catch (err) {
		next(err);
	}
});

module.exports = app
```
## I'm working on a programming language! Look in the pinned repositories to learn more.
