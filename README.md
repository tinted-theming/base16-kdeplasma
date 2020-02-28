<p float="left">
<a href="../../"><img src="https://img.shields.io/github/languages/top/Base24/base16-kdeplasma.svg?style=flat-square" alt="Github top language"></a>
<a href="../../"><img src="https://img.shields.io/github/repo-size/Base24/base16-kdeplasma.svg?style=flat-square" alt="Repository size"></a>
<a href="../../issues"><img src="https://img.shields.io/github/issues/Base24/base16-kdeplasma.svg?style=flat-square" alt="Issues"></a>
<a href="/LICENSE.md"><img src="https://img.shields.io/github/license/Base24/base16-kdeplasma.svg?style=flat-square" alt="License"></a>
<a href="../../commits/master"><img src="https://img.shields.io/github/commit-activity/m/Base24/base16-kdeplasma.svg?style=flat-square" alt="Commit activity"></a>
<a href="../../commits/master"><img src="https://img.shields.io/github/last-commit/Base24/base16-kdeplasma.svg?style=flat-square" alt="Last commit"></a>
</p>

# base16-kdeplasma

<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">

Base 16 themes for KDE Plasma

**Find themes under [output/kdeplasma/schemes](output/kdeplasma/schemes)**

**Find blue themes under [output/kdeplasma/schemes-blue](output/kdeplasma/schemes-blue)**
**Find green themes under [output/kdeplasma/schemes-green](output/kdeplasma/schemes-green)**
**Find purple themes under [output/kdeplasma/schemes-purple](output/kdeplasma/schemes-purple)**

## Build it yourself
### Use the builder in this repo
I've modified the builder from: https://github.com/InspectorMustache/base16-builder-python


1. Run
```python
./pybase16.py update
```
2. Run
```python
./pybase16.py build
```

#### Changes

1. pybase16_builder/updater.py (no longer clones templates)
2. pybase16_builder/builder.py TemplateGroup, build() template_dirs variable

### Or go to the source
1. Find yourself a builder from https://github.com/chriskempson/base16#builder-repositories
2. I used the Python builder
```python
python3 -m pip install pybase16-builder
```
3. Make a temporary directory
4. Run
```python
pybase16 update
```
5. Remove the contents of the templates/ directory and replace with the root
directory of this repo (so that /templates/ is kdeplasma/templates/)
6. Run
```python
pybase16 build
```

## Changelog
See the [CHANGELOG](/CHANGELOG.md) for more information.


## Download
### Clone
#### Using The Command Line
1. Press the Clone or download button in the top right
2. Copy the URL (link)
3. Open the command line and change directory to where you wish to
clone to
4. Type 'git clone' followed by URL in step 2
```bash
$ git clone https://github.com/FredHappyface/base16-kdeplasma
```

More information can be found at
<https://help.github.com/en/articles/cloning-a-repository>

#### Using GitHub Desktop
1. Press the Clone or download button in the top right
2. Click open in desktop
3. Choose the path for where you want and click Clone

More information can be found at
<https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop>

### Download Zip File

1. Download this GitHub repository
2. Extract the zip archive
3. Copy/ move to the desired location


## Licence
MIT License
Copyright (c) Base24
Copyright (c) FredHappyface
(See the [LICENSE](/LICENSE.md) for more information.)
