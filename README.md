```zsh
> npm i epicrafter --save
```

```js
const { Profile } = require('merlax');

const user = new Profile({
	name: "Oscar Bréhier",
	age: "18",
	description: "Full stack web developer and designer",
	speaks: ["French", "English"],
	location: "Athens GR",
	languages: ["JavaScript", "HTML", "CSS", "Java", "Python"], 
	tools: ["NodeJS", "React"],
	socials: {
		discord: "Epicrafter#4261",
		github: "https://github.com/oscarbrehier",
		instagram: "https://instagram.com/brh.oscar",
		email: "brehieroscar@gmail.com"
	} 
});

user.giveBirth();

```
