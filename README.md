```zsh
> npm i epicrafter --save
```

```js
const { Profile } = require('merlax');

const user = new Profile({
	name: "André Merlaux",
	age: "16",
	description: "Full stack web developer and designer",
	speaks: ["French", "English"],
	location: "Athens GR",
	languages: ["JavaScript", "HTML", "CSS", "Java"], 
	tools: ["NodeJS", "React"],
	socials: {
		discord: "Epicrafter#4261",
		email: "fancypig10@gmail.com",
		github: "https://github.com/andremerlaux"
	} 
})
```
