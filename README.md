![github-banner.png](http://i.imgur.com/61OLE5Z.png)
<p align="center" style="text-align:center">
  <img src="http://i.imgur.com/bnxdjg9.png"/>
</p>

<p align="center" style="text-align:center">
<a href="https://github.com/720kb/ndm/releases" target="_blank">
<img src="https://img.shields.io/github/release/720kb/ndm.svg"/>
</a>
<a href="https://github.com/720kb/ndm/blob/master/LICENSE.md" target="_blank">
<img src="https://img.shields.io/aur/license/yaourt.svg"/>
</a>
<a href="https://gitter.im/720kb/ndm" target="_blank">
<img src="https://img.shields.io/gitter/room/ndm/ndm.js.svg"/>
</a>

</p>

###What is this ?

**ndm** formally _"Npm Desktop Manager"_ is the desktop GUI for npm.

With **ndm** you can easily manage npm and npm packages directly from the couch, without any worries.

It is based on the [npm-cli](https://docs.npmjs.com/cli/npm) and developed over [Electron](https://github.com/electron/electron) with some touch of AngularJS and Sass.

Feel free to reach any of us for any info/question, or to support the project in any way you wish.

###I love the Shell, why use an app?

Of course, we all love it too.

The Shell is obviously very powerful.

However: not all the people know how to use it from the scratch.

Sometimes and very often, they can not use the Shell for intern/office/job reasons, or they are not willing to use it at all.

Some of the value added of **ndm** we believe:

You don't have to struggle with multiple terminal tabs or to go through the shell logs for checking warnigs and errors. You have all your projects, logs, errors, warnings, informations, in one single intuitive interface.

You get notified as a process has finished.

You can list all the packages inside a project in a friendly way; see the common informations about every single package installed in one click.

You can edit project package.json in-place, "Snapshot" projects and revert them from the "History" to try any changes before the time (i.e: update pkgs, install new pkgs, delete pkgs, and so on..).

Commit after commit, PR after PR, this list will get bigger we think.

**Forget not that:** using ndm doesn't mean you can no longer use the Shell and viceversa.

###Download

Download the latest **ndm** release **[here](https://github.com/720kb/ndm/releases/)**

###Develop

_Setup_

`$ git clone <repo> && cd ndm`

`$ npm install`

_Run app_

`$ npm start`


###Build

If you want to make your own executable:

`$ git clone <repo> && cd ndm`

`$ npm install`

Adjust `package.json`  "[build](https://github.com/720kb/ndm/blob/master/package.json)" field according on how [electron-builder](https://github.com/electron-userland/electron-builder) works, then just run:

`$ npm run build`


###Contribute

We'll be much grateful if you help and contribute to the project, in any way you can or wish.
Feel free to contribute by forking, opening issues, pull requests and whatever you think it's important for the project.

Doors are wide open!

Below are the few guidelines to follow, in case, just that!

[Contributing Guidelines](https://github.com/720kb/ndm/blob/master/CONTRIBUTING.md)

###License

GNU GPLv3 [License](LICENSE.md).

###Recommendations

- Is highly recommended to install node and npm via Brew or Nvm or N
- Is highly recommended to not start the app with `sudo` when developing or testing (WRONG! `sudo npm start`)
- Is recommended to not rename `node_modules/` folder in your projects
- Is recommended to snapshot projects inside ndm (Right click on a project -> snapshot) so that: any change or edit to the project can be reverted from the project History (Right click on a project -> History)
- Is recommended to manage only `.git` projects with ndm (so that everything can be reverted to it's previous status)
- Is recommended to install and use always the LTS nodejs version

###FAQ
**Is ndm stable?**

The first releases are not guaranteed to be very stable, some problem/bug may happen.

Just give it time, have some patience and, if you would, please contribute by forking, PR and/or creating issues, your help is always appreciated.

**Do i have to worry about anything when using ndm?**

Actually not, not really.
ndm does not run any malicious or env/system breaking commands in background, and it doesn't run anything outside npm native commands.
If you want to be 100% sure about this, just look at the source code, which is clear and very readable.

**Why is so slow on my pc?**

ndm speed depends exclusively on your pc/device specs and [npm-cli](https://docs.npmjs.com/cli/npm) speed.
We can't do much to speed up your computer or the npm commands.

**Yarn?**

Yarn is a great tool: we are looking forward to seeing what happens, also because it is a brand new project and many things could change in the meantime. That said: if you have any idea or suggestion: here you're welcome to share and discuss!


**Why Mac only?**

We now focus on one OS but the app is developed keeping in mind that it will have to run also on other OSs. We won't _put too much meat on bbq_ for the moment, it is now very important to obtain an OS-abstracted and stable app.

As soon as we are sure that the project is stable, it will be delivered to the other OSs.

**Support?**

Just open an issue we'll be in touch.

###Who we are

[720kb](https://720kb.net)
