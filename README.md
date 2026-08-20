# Galette Redmine Theme

This a customized version of [Opale Redmine Theme](https://github.com/gagnieray/opale) made with [Custom Opale Redmine Theme Builder](https://github.com/gagnieray/custom-opale-builder) for the [Galette](https://galette.eu) project.

## Essential commands

### On first clone

```bash
git clone --recurse-submodules git@github.com:galette/theme-redmine.git
```

### For future pulls

```bash
git pull --recurse-submodules
```

Or make Git automatically initialize and update submodules during pulls:

```bash
git config submodule.recurse true
```

Then a normal `git pull` will update _Opale Redmine Theme_ submodule at the same time.

### To (re)build the theme

```bash
./build -n opale_galette -o {PATH_TO_REDMINE_THEMES_FOLDER}
```

More details about the build process and command line options on [Custom Opale Redmine Theme Builder](https://github.com/gagnieray/custom-opale-builder).

## Copying

This theme is licensed under the [GNU Affero General Public License v3.0 or later](https://www.gnu.org/licenses/agpl-3.0), the text of which can be found in [LICENSE](https://github.com/galette/theme-redmine/blob/master/LICENSE).

Licensing of included components:

- _Opale Redmine Theme_ submodule is released under the [GNU Affero General Public License v3.0 or later](https://github.com/gagnieray/opale/blob/master/LICENSE).
- _Galette_ favicon in the `src/favicon` directory is released under the [GPL-3.0 license](https://github.com/galette/galette/blob/master/LICENSE.md).
- _PT Sans_ webfont files in the `src/webfonts` directory are released under the [SIL Open Font License](https://github.com/librefonts/ptsans/blob/master/OFL.txt).
