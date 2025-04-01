1> make a npm repositries
2> npm init to initialize git repositries
3> git add .  (in terminal)
4> git commit -m "add initial files for backend" (in terminal)
5> create a repo in git hub of project
6> git branch -M main (in terminal to rename master to main)
7> git remote add origin https://github.com/SauravKu26/backend_project.git (adding remote in terminal from github)
8> git push -u origin main

9> make folder public > (folder)temp > (file ) .gitkeep
10> make gitignore file.
11> go to gitignore generator(website) and choose for nodejs and copy all content and paste in gitignore file.
12> make environment variable file -> .env (in video .env.sample bcs .env give error).

12> make src folder. (in this make app.js, index.js, constants.js file).

13> "type": "module", in package.json after line 4 (bcs import works in module)

14> { npm install -D nodemon}, devdependencies install nodemonn (it helps in server restart as the file save).
15> change test command with dev command { "dev": "nodemon src/index.js" } in script tag line 8 of package.json

16> make folders in src using  { controllers db middlewares models routes utils } folders.
