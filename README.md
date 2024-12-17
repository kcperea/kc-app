# kc-app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.13.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


## Angular Learning step by step
install nvm
1. download nvm
2. open and install
3. open command prompt
4. type	nvm -v    (check version)
5. nvm list	  (ano mga naka install) kung wala
6. type nvm install 16
7. 	nvm use 16
8. 	node -v
9. 	npx -v
11. dir 			(directory)
12. mkdir kc			(create folder)
13. cd kc			(go to folder type)
14. npm install @angular/cli@14	(install CLI in kc folder)
15. dir				(check installed in folder kc)
16. dir node_module		(check installed in folder kc)
17. tyoe ng 
18. ng new kc-app		(create new web app)
19. css				(choose stylesheet)
20. cd kc-app			(change directory to kc-app)
21. ng serve --open		(open and creating local host)
22. error different version should be 16
23. notepad package-lock.json	(open and check the exsiting version in dependency)
24. https://stackoverflow.com/a/79276733/28766039 (answer, to remove and override node dependency version 16)
25. npm install 		(sync package lock.json)
26. ng serve --open		(open and creating local host without error http://localhost:4200/)
27. download git dearch in browser (to check all changes)
28. git -v
29. ssh-keygen -t ed25519 -C "kclyn.perea@gmail.com" (to connect pc to github)
30. open github account 
31. go to setting
32. shh
33. new shh key
34. add title and copy paste the key created 

35. create new repository on github account (for online backup)
36. same name to your web app kc-app
37. git init	(in cmd)
38. go to github account check your repository follow the instruction
	git init
	git add .			
	git commit -m "first commit"
	git branch -M main
	git remote add origin git@github.com:kcperea/kc-app.git
	git push -u origin main

39. save your notes in readme 
40. go to vscode click readme
41. copy paste your notes 
42. go to cmd type git status
43. git add readme.md
44. git status 		(green text means added to next commit)
45. git commit -m "track my progress"


46. Change computer set up
47.  search ssh keygem docs
48. open cmd or terminal
49. copy paste keygem docs code
50. open notepad ... pub
51. create new ssh key in github, paste pub key
52. open vscode terminal
53. git clone git@github.com:kcperea/kc-app.git
54. code kc-app, commit and push won't work yet
55. git config --global user.name "kc.perea" ; required to commit
56. git config --global user.email 'kclyn.perea@gmail.com" ; required to commit
57. use IDE to push changes or $ git add . 
58. git commit -m "Setting up on another computer" 
59. git push
