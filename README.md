<h1>Hi there! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h1>

<h3>Who am I?</h3> 

```Node
const app = require("express").Router()

app.get("/Info", async (req, res, next) =>{
	try{
		const sendInfo = {
			"Nickname": "Marel",
			"Languages": ["NodeJS", "TypeScript", "ReactJS", "HTML", "CSS", "Python"]
			"Description": "I'm Loris, and I work as a MERN Stack developer.
			Started years ago with some C++ I then abandoned coding.
			I started another time 7 months ago thanks to Strive School"
		};
		res.status(200)send(sendInfo);
	} catch (err) {
		console.log(err);
		next(err);
	}
});

module.exports = app
```

<h3>My stats</h3> 

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=marelguy&show_icons=true&theme=radical)

 ### On what am i working on?
 - Currently doing a clone of [scpwiki.com](http://scpwiki.com)
 - Trying to improve my newbie python skills
 - Playing Tom's Clancy: Ghost Recon Wildlands

<h3> Where can you find me?</h3>

 - [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/averagehikikomori/)
 - [![StackOverflow Badge](https://img.shields.io/badge/-StackOverflow-red?style=flat-square&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/14378513/loris-cuntreri?tab=profile)
 - [![Twitch Badge](https://img.shields.io/badge/-Twitch-purple?style=flat-square&logo=twitch&logoColor=white)](https://ww.twitch.tv/MarelGuy)
