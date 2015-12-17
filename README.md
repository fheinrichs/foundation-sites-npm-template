# Foundation for Sites Template

**Please open all issues with this template on the main
[Foundation for Sites (npm)](https://github.com/fheinrichs/foundation-sites-npm-template/issues) repo.**

This is the basic starter project for
[Foundation for Sites 6](http://foundation.zurb.com/sites) using only npm (w/o)
bower. It includes a Sass compiler and a starter HTML file for you.


## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.10 or greater)
- [Git](https://git-scm.com/)

This template should be downloaded and set up manually.

*Note*: If you prefer an isolated nodejs environment and are comfortable with
[python](https://www.python.org/) and [virtualenv](https://virtualenv.readthedocs.org/en/latest/)
(like me), checkout the **awesome** [nodeenv](https://github.com/ekalinin/nodeenv)
project.


### Manual Setup (Git)

To manually set up the template in your project, first create your project
folder and initialize an empty git repository:

```bash
mkdir myproject
cd projectname
git init
```

Then add the template as upstream repository and download its contents
download it with Git:

```bash
git remote add upstream https://github.com/fheinrichs/foundation-sites-npm-template.git
git pull upstream master
```

Then open the folder in your command line, and install the needed dependencies:

```bash
npm install
```

Finally, run `npm start` to run the Sass compiler and let it watch your scss
directory. It will re-run every time you save a Sass file.

If you don't want the observing behavior, e.g., if you trigger this from
another build chain or manually, you can run this task with
```npm run build```.

### Manual Setup (w/o Git)

Instead of adding the template as upstream remote, you can also simply grab its
contents as [zip file](https://github.com/fheinrichs/foundation-sites-npm-template/archive/master.zip)
and extract them in your project directory. The other steps are similar.