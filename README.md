## Material and Mouse driven theme for [AwesomeWM 4.3](https://awesomewm.org/) 

# This project was a workflow prototype and was the base of my new project [Material Shell](https://github.com/PapyElGringo/material-shell) and therefore is now unmaintained.

### You should check [HikariKnight/material-awesome](https://github.com/HikariKnight/material-awesome) or [ChrisTitusTech/material-awesome](https://github.com/ChrisTitusTech/material-awesome) forks for updated versions.


An almost desktop environment made with [AwesomeWM](https://awesomewm.org/) following the [Material Design guidelines](https://material.io) with a performant opiniated mouse/keyboard workflow to increase daily productivity and comfort.

[![](./theme/PapyElGringo-theme/demo.gif?raw=true)](https://www.reddit.com/r/unixporn/comments/anp51q/awesome_material_awesome_workflow/)
*[Click to view in high quality](https://www.reddit.com/r/unixporn/comments/anp51q/awesome_material_awesome_workflow/)*

| Tiled         | Panel         | Exit screen   |
|:-------------:|:-------------:|:-------------:|
|![](https://i.imgur.com/fELCtep.png)|![](https://i.imgur.com/7IthpQS.png)|![](https://i.imgur.com/rcKOLYQ.png)|



## Installation

### 1) Get all the dependencies
- [AwesomeWM](https://awesomewm.org/) as the window manager
- [Roboto](https://fonts.google.com/specimen/Roboto) as the **font**
- [Rofi](https://github.com/DaveDavenport/rofi) for the app launcher
- [Compton fork](https://github.com/tryone144/compton) for the compositor (blur and animations)
- (Optional) [Materia](https://github.com/nana-4/materia-theme) as GTK theme
- (Optional) [Papirus Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) as icon theme
- (Optional) [lxappearance](https://sourceforge.net/projects/lxde/files/LXAppearance/) to set up the gtk and icon theme

### 2) Clone the configuration. Works with awesome 4.3 stable

```
git clone https://github.com/prakash2033/material-awesome.git ~/.config/awesome
```

### 3) Set the themes
Start **lxappearance** to active the **icon** theme and **GTK** theme

### 4) Read the documentation
The documentation live within the source code.

The project is split in functional directories and in each of them there is a readme where you can get additionnal informations about the them.

* [Configuration](./configuration) is about all the **settings** available
* [Layout](./layout) hold the **disposition** of all the widgets
* [Module](./module) contain all the **features** available
* [Theme](./theme) hold all the **aestetic** aspects
* [Widget](./widget) contain all the **widgets** available
