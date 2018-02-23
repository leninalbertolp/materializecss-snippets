# Materializecss Snippets for Sublime Text 2&3 DEPRECATED
![GitHub release](https://img.shields.io/badge/release-1.2.3-green.svg) [![GitHub forks](https://img.shields.io/github/forks/leninalbertolp/materializecss-snippets.svg)](https://github.com/leninalbertolp/materializecss-snippets/network) [![GitHub stars](https://img.shields.io/github/stars/leninalbertolp/materializecss-snippets.svg)](https://github.com/leninalbertolp/materializecss-snippets/stargazers) [![GitHub issues](https://img.shields.io/github/issues/leninalbertolp/materializecss-snippets.svg)](https://github.com/leninalbertolp/materializecss-snippets/issues)

## Changelog
V-1.2.3 (September 2017/09)
- Updated the link CDN for CSS, JS file to 0.100.2

V-1.1.3 (April 2017/04)
- Updated the link CDN for CSS, JS file to 0.98.2 and jQuery files to 3.2.1
- Updated structure HTML template snippets cdn and local
- Added New Snippet: FAB to Toolbar (mz-btn:fab-toolbar)
- Added New Snippet: Swipeable Tabs (mz-tabs:swipeable)
- Added New Snippet: Card with small Floating Action Button (mz-card:fab-small)
- Added New Snippet: Card with large Floating Action Button (mz-card:fab-large)
- Added New Snippet in javascript component: Feature Discovery (mz-featurediscovery:tap-target)
- It rewrote the structure of snippets for better semantics in the work area (see table of contents)
- Removed snippets that were not a block of code, such as: Helpers, Shadow, Parallax etc...
- Bugs Fixed

V-1.0.2 (December 2016/06)
- Updated CDN Links to 0.97.8
- Added New Snippet: Tabs now supported in navbar (mz-navbar: with_tabs)
- Bugs Fixed

V-1.0.1 (August 2016/09)
- Updated CDN Links to 0.97.7
- Added New Snippet: for Horizontal Card
- Added New Snippet: for Carousel
- Added New Snippet: for Sidenav
- removed files for requesting addition to Package Control ([more details here
 ](https://github.com/wbond/package_control_channel/pull/5591))

V-1.0.0 (May 2016/27)
- Initial version
- Application of adhesion to package control

## Introduction.
first of all, Sorry for my horrible English, is not my native language. :flushed:

Repository with snippets of the framework Materilizecss to Sublime Text 2&3, which will help you streamline your workflow, and make time for a cup of coffee :coffee:

For now, you can only install this repository downloading snippets, I'm working to take it as a plugin and upload to Package Control.

## Installation.

### PackageControl Installation (Not available, sorry there is already a similar plugin Package Control). :cry:

You can install this awesome plugin through the [Package Control](https://packagecontrol.io/installation).

1. Press <kbd>cmd/ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd> to open the command palette.

2. Type *"install package"* and press enter. Then search for *"Materializecss snippets"*

### Manual Installation

1. Download this repository, unpack the .zip and rename the folder materializecss-snippets-master to materializecss-snippets

2. Open Sublime Text and go to Preferences> Browse Packages ...> User, and move the materializecss-Snippets folder to this route, that's all, enjoy.

## How to use.

To invoke snippets must type **mz-** more the element name. Example: **mz-table**.

![](http://i.imgur.com/yXBfI25.jpg)

To have the drop-down menu showing snippets more content like the following image, you must install the plugin [SublimeCodeIntel from PackageControl](https://packagecontrol.io/packages/SublimeCodeIntel), what contratio will have to manually search each snippet.

![](http://i.imgur.com/tVGerJc.gif)

## Table of Contents

Remember to use **mz-** more the name of the element to invoke snippets.

## Template
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-template: | cnd | Basic html structure using cdn files |
| mz-template: | local | Basic html structure using local files |
| mz-template: | grid | Basic grid structure |

## CSS
### mediacss
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-mediacss: | img-circular | Circular Image |
| mz-mediacss: | img-responsive | Responsive Image |
| mz-mediacss: | video-embeds | Embeds video |
| mz-mediacss: | video-responsive | Responsive Video |

### table
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-table: | bordered | Bordered Table |
| mz-table: | centered | Centered Table |
| mz-table: | default | Default Table |
| mz-table: | highlight | Highlight Table |
| mz-table: | responsive | Responsive Table |
| mz-table: | striped | Striped Table |

### typography
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-typography: | blockquote | Blockquote |
| mz-typography: | flow-text | Responsive Text |

## Components
### badge
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-badge: | default | Default Badge |
| mz-badge: | new | New Badge |

### breadcrumb
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-breadcrumb: | breadcrumb | Breadcrumb|

### buttons
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-btn: | default | Default Button|
| mz-btn: | disabled | Disabled Button|
| mz-btn: | fab-ct-h | Fixed action button click to toggle horizontal|
| mz-btn: | fab-ct-v | Fixed action button click to toggle vertical|
| mz-btn: | fab-h | Fixed action button horizontal|
| mz-btn: | fab-toolbar | Fixed action button toolbar|
| mz-btn: | fab-v | Fixed action button vertical|
| mz-btn: | flat | Button Flat|
| mz-btn: | flat-disabled | Button flat disabled |
| mz-btn: | floating | Button Floating|
| mz-btn: | floating-disabled | Button Floating Disabled|
| mz-btn: | icon-left | Button with icon to the left |
| mz-btn: | icon-right | Button with icon to the right|
| mz-btn: | large | Large Button|
| mz-btn: | large-disabled | Large Button Diasbled|
| mz-btn: | large-icon-left | Large button with icon on the left|
| mz-btn: | large-icon-right | Large button with icon on the right|
| mz-btn: | submit | Submit Button|
| mz-btn: | fab-toolbar | Fixed action button toolbar|

### card
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-card: | basic | Basic Card|
| mz-card: | fab-large| Card with large Floating Action Button|
| mz-card: | fab-small| Card with small Floating Action Button|
| mz-card: | panel | Panel Card|
| mz-card: | horizontal | Horinzontal Card|
| mz-card: | image | Image Card|
| mz-card: | image-lg | Image Card Large|
| mz-card: | image-md | Image Card Medium|
| mz-card: | image-sm | Image Card Small|
| mz-card: | rao-default | Card reveal action option default|
| mz-card: | rao-lg | Card reveal action option large|
| mz-card: | rao-md | Card reveal action option medium|
| mz-card: | rao-sm | Card reveal action option small|
| mz-card: | reveal-default | Card reveal default|
| mz-card: | reveal-lg | Card reveal large|
| mz-card: | reveal-md | Card reveal medium|
| mz-card: | reveal-sm | Card reveal small|

### chips
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-chips: | contact | Chip Contacts|
| mz-chips: | tags | Chip Tags|
| mz-chips: | tags-close | Chip tag with icon close|

### collections
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-collections: | avatar | Avatar Collection|
| mz-collections: | basic | Basic Collection|
| mz-collections: | dismissable-content | Dismissable Content collection|
| mz-collections: | headers | headers collection|
| mz-collections: | link | Link Collection|
| mz-collections: | link-active | Link active collection|
| mz-collections: | secondary-content | Secondary Content Collection|

### footer
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-footer: | default | Footer Default|

### forms
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-forms: | contact | Contact Form|

### icons
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-icons: | default | Default Icon|
| mz-icons: | lg-icon | Large Icon|
| mz-icons: | md-icon | Medium Icon|
| mz-icons: | sm-icon | Small Icon|
| mz-icons: | tn-icon | Tiny Icon|

### navbar
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-navbar: | full_width | Menu full width|
| mz-navbar: | full-width-fixed | Menu fixed full width|
| mz-navbar: | width-centered | Menu width centered|
| mz-navbar: | width-centered-fixed | Menu fixed width centered|
| mz-navbar: | with-tabs | Menu with tabs|

### pagination
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-pagination: | default | Pagination Default|

### preloader
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-preloader: | circular-flashing-colors-lg | Preloader circular flashing colors big|
| mz-preloader: | circular-flashing-colors-default | Preloader circular flashing colors default|
| mz-preloader: | circular-flashing-colors-sm | Preloader circular flashing colors small|
| mz-preloader: | color-circular-lg | Preloader color circular big|
| mz-preloader: | color-circular-default | Preloader color circular default|
| mz-preloader: | color-circular-sm | Preloader color circular small|
| mz-preloader: | linear-determinate | Preloader linear determinate|
| mz-preloader: | linear-indeterminate | Preloader linear indeterminate|

## JavaScript
### carousel
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-corousel: | default | Default Carousel|
| mz-corousel: | full-width | Carousel full width|
| mz-corousel: | special-options | Special options carousel|

### collapsible
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-collasible: | accordion | Collapsible accordion|
| mz-collasible: | expandable | Collapsible expandable|
| mz-collasible: | popout | Collapsible popout|

### dialogs
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-dialogs: | callback-toast | Callback Toast|
| mz-dialogs: | rounded-toast | Rounded Toast|
| mz-dialogs: | toast-default | Default Toast|
| mz-dialogs: | tooltips-bottom | Tooltips Bottom|
| mz-dialogs: | tooltips-left | Tooltips Left|
| mz-dialogs: | tooltips-right | Tooltips Right|
| mz-dialogs: | tooltips-top | Tooltips Top|

### dropdown
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-dropdown: | dropdown | Dropdown Structure|

### featurediscovery
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-featurediscovery: | tap-target | Tap Target|

### mediajs
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-mediajs: | material-box | Material design lightbox|
| mz-mediajs: | material-box-captions | Material design lightbox captions|
| mz-mediajs: | slider | Material design slider|
| mz-mediajs: | slider-fullscreen | Material design slider fullscreen|

### modals
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-modals: | bottom-sheet | Bottom Sheet Modal|
| mz-modals: | default | Default Modal|
| mz-modals: | fixed-footer| Fixed Footer Modal|

### sidenav
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-sidenav: | dropdown-structure | Sidenav Dropdown|
| mz-sidenav: | fixed-structure | Sidenav Fixed|
| mz-sidenav: | fullscreen-structure | Sidenav Fullscreen|
| mz-sidenav: | html-structure | Sidenav HTML Structure|

### tabs
| Snippet | Snippet Content | Description |
|---------|-----------------|-------------|
| mz-tabs: | default | Default Tab|
| mz-tabs: | swipeable | Swipeable tab|
