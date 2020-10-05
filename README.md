# [opthamed.sk](https://opthamed.sk/)

My personal blog. Forked from [Gatsby blog starter](https://github.com/gatsbyjs/gatsby-starter-blog). Syntax theme based on [Sarah Drasner's Night Owl](https://github.com/sdras/night-owl-vscode-theme/) with small tweaks.

To run locally, `yarn`, then `yarn dev`, then open https://localhost:8000.

Deploy

```
cd public;
tar czf - * | ssh ophthamed@37.205.14.173 "cd /home/ophthamed/public_html/ && tar xvzf -"
```
