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
  - open your [terminal](https://en.wikipedia.org/wiki/Command-line_interface) and type `npm install -g eslint`
2. install [Atom Editor](https://atom.io/)
  - watch introductionary [video](https://www.youtube.com/watch?v=Y7aEiVwBAdk).
  - forget about mouse - learn [shortcodes](https://atom.io/docs/v1.2.4/using-atom-moving-in-atom)
3. install [Git](https://git-scm.com/downloads)
4. do a back up for your Atom configs. (unix:`mv ~/.atom ~./atom_bk`)
5. `git clone https://github.com/FrontendLabEpam/FLE_Atom.git ~/.atom` to replace your configs with those in these repository
6. install listed packages with `apm install --packages-file ~/.atom/package-list.txt`
