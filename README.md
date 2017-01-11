# Angular2 with kendo set up.


<h2> This Set includes Kendo UI for Angular 2 </h2>
<p> In Properly build you must have an account with Telerik.</p>
<p> Please follow these instructions with Telerik before installing.</p>
<p><a href="http://www.telerik.com/kendo-angular-ui/getting-started/"> Telerik Link</a></p>
<p>&nbsp;</p>
<hr/>
<p>This repository holds the TypeScript source code of the <a href="https://angular.io/docs/ts/latest/quickstart.html">angular.io quickstart</a>, the foundation for most of the documentation samples and potentially a good starting point for your application.
</p><p>
It's been extended with testing support so you can start writing tests immediately.</p>
<p>
This is not the perfect arrangement for your application. It is not designed for production. It exists primarily to get you started quickly with learning and prototyping in Angular.</p>
## Prerequisites

Node.js and npm are essential to Angular development. 
    
<a href="https://docs.npmjs.com/getting-started/installing-node" target="_blank" title="Installing Node.js and updating npm">
Get it now</a> if it's not already installed on your machine.
 
**Verify that you are running at least node `v4.x.x` and npm `3.x.x`**
by running `node -v` and `npm -v` in a terminal/console window.
Older versions produce errors.

We recommend [nvm](https://github.com/creationix/nvm) for managing multiple versions of node and npm.

## Create a new project based on the QuickStart

Clone this repo into new project folder (e.g., `my-proj`).
```shell
git clone https://github.com/angular/quickstart  my-proj
cd my-proj
```

We have no intention of updating the source on `angular/quickstart`.
Discard the `.git` folder..
```shell
rm -rf .git  # OS/X (bash)
rd .git /S/Q # windows
```
### Delete _non-essential_ files (optional)

You can quickly delete the _non-essential_ files that concern testing and QuickStart repository maintenance
(***including all git-related artifacts*** such as the `.git` folder and `.gitignore`!)
by entering the following commands while in the project folder:

##### OS/X (bash)
```shell
xargs -a non-essential-files.txt rm -rf
rm app/*.spec*.ts
rm non-essential-files.txt
```

##### Windows
```shell
for /f %i in (non-essential-files.txt) do del %i /F /S /Q
rd .git /s /q
rd e2e /s /q
```

### Create a new git repo
You could [start writing code](#start-development) now and throw it all away when you're done.
If you'd rather preserve your work under source control, consider taking the following steps.

Initialize this project as a *local git repo* and make the first commit:
```shell
git init
git add .
git commit -m "Initial commit"
```

>Recover the deleted `.gitignore` from the QuickStart repository 
if you lost it in the _Delete non-essential files_ step.

Create a *remote repository* for this project on the service of your choice.

Grab its address (e.g. *`https://github.com/<my-org>/my-proj.git`*) and push the *local repo* to the *remote*.
```shell
git remote add origin <repo-address>
git push -u origin master
```
## Install npm packages

Navigate to you project using your command prompt or Terminal then follow the install below.

Install the npm packages described in the `package.json` and verify that it works:

```shell
npm install
npm start
```

