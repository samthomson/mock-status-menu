# mock-status-menu

created to test out using a subtree repo (this one) as part of several static sites operated by status.

The goal is that this repo would contain some partials (header and footer menus). Ideally style and JS should be part of this repo and therefor not duplicated in the 'parent' repos (static sites) that will make use of this menu.

## Addding this repo/folder of partials to an existing static hexo site

`cd` from the projects root down into themes > [current theme, navy?] > layout > partial, you can then run `git submodule add https://github.com/samthomson/mock-status-menu mock-status-menu`

Two key parameters: the repo you're pulling, and the relative folder to clone it into. It's from this folder that you will include the shared partials, from whatever swig template you're embedding them in.


git@github.com:samthomson/mock-status-menu.git