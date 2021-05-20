this is a Gatsby theme for a static site based on lists. lists are interesting, in computer science and outside of computer science. i think in lists a lot. 

the idea here is that you'd be able to add a markdown file for a _thing_ (think, like, a [one-line hack](https://connorrothschild.github.io/one-line-hacks/) or a [quote catalogue](https://arcana.computer/catalogs/quotes), or [paper summaries](https://deblnia.github.io/speedyscholar/), or [something you learned](https://tilearned.netlify.app/)) and that _thing_ then becomes nicely laid out, fully-searcable, tagged, and on the web. 


up-and-running: 

```
npm i //or npm install 
gatsby develop
``` 

more plugins: 

```
npm install [PLUGIN NAME]
``` 


build: 

```
gatsby build 
netlify deploy -d . --prod
```

you may need to [set up the netlify cli](https://www.gatsbyjs.com/docs/recipes/deploying-your-site/#deploying-to-netlify).

## References

- [Adding Markdown Pages](https://www.gatsbyjs.com/docs/adding-markdown-pages/)
