### Front End Lab Atom configs and packages

A set of configs and packages to ensure students spend less time on errors,
includes plugins for:
- [ESLint](http://eslint.org/)
- [HTMLHint](http://htmlhint.com/)
- [CSSLint](http://csslint.net/)
- [W3C validator](https://validator.w3.org/)
- [and more...](https://github.com/FrontendLabEpam/FLE_Atom/blob/master/package-list.txt)

#### Instructions

1. install [Node.js](https://nodejs.org/en)
  - open [terminal](https://en.wikipedia.org/wiki/Command-line_interface) and ensure successful instalation: `node -v`, `npm -v`
  - type `npm install -g eslint`
    - if system errors with permission denied, try `sudo npm install -g eslint`
2. install [Atom Editor](https://atom.io/)
  - open terminal and ensure you can access atom and [apm](https://github.com/atom/apm): `apm -v`
    - if system errors, open Atom manually, in atom menu click `Install Shell commands`
      - windows7: might be you don't have option above, you would need to add `apm` manually into [PATH](http://geekswithblogs.net/renso/archive/2009/10/21/how-to-set-the-windows-path-in-windows-7.aspx)
  - watch introductionary [video](https://www.youtube.com/watch?v=Y7aEiVwBAdk)
  - forget about mouse - learn [shortcodes](https://atom.io/docs/v1.2.4/using-atom-moving-in-atom)
3. install [Git](https://git-scm.com/downloads)
  - open git bash, type `git --version` to ensure some programs have aliases like `-v` and some - not
4. rename your current configs folder
  - unix or from git bash: `mv ~/.atom ~./atom_bk`
  - [windows](https://en.wikipedia.org/wiki/Ren_(command)): `ren .atom atom_bk`
  - or just remove it if you are brave enough
5. copy our configs: `git clone https://github.com/FrontendLabEpam/FLE_Atom.git ~/.atom`
6. install listed packages with `apm install --packages-file ~/.atom/package-list.txt`
7. if you have faced problems with some particular package, you may try to install it manually in atom:
  - press `ctrl + ,`, 'Install', search for [packages](https://github.com/FrontendLabEpam/FLE_Atom/blob/master/package-list.txt)


#### GIFS

1. ensure node paths in terminal
  ![](http://imgur.com/OBzUGxp.gif)

2. ensure apm, git clone configs, install packages
  ![](http://imgur.com/LvVwcjv.gif)

3. for troubles with windows
  ![](http://i.imgur.com/FebnXar.gif)
