# hexo-theme-jpdynamicscrm

hexo theme for jpdynamicscrm tech blog

> forked from [hexo-theme-landscape](https://github.com/hexojs/hexo-theme-landscape)

## Set Up

```sh
git clone https://github.com/jpdynamicscrm/hexo-theme-jpdynamicscrm.git themes/jpdynamicscrm
npm i -D hexo-generator-feed
npm i -D jpdynamicscrm/hexo-helper-github-issues hexo-generator-root-tag
```

## hexo config.yml


```yml
root_tag_generator:
  root_tag_names:
    - Information
    - CanvasApp
    - Customization
    - ModelDrivenApp
    - OnlineSystem
    - Other
    - Archive
    - PortalApp
    - PowerAutomate
    - PowerPlatform
    - PowerVirtualAgents
  sub_tag_limit: 20
  
github:
  url: https://jpdynamicscrm.github.io/blog/
  posts_dir: articles

```
