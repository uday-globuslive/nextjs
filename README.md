# install nodejs
- Download from [LTS](https://nodejs.org/en)
- check installation:
  - ```npm --version```
  - ```node --verion```

# Create sample nextjs project
- Refer from [nextjs](https://nextjs.org/docs/getting-started/installation)
- ![create project command](img/01.jpg)
- Some times you get error while installing, so create this folder C:\Users\uday1\AppData\Roaming\npm
- Test app: ```cd <project_folder> ; npm run dev```

## Routing based on folder structure. sub folders can be loaded as urls.
- create a file  in app\awesome\page.js
```
export default function AwesomePage(){
	return (
	<main>
	  <h1>NextJS Is Awesome!</h1>
	</main>
	)
}
```
- should work http://localhost:3000/awesome
