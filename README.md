# adamist521.github.io


`gatsby-site/node_modules/gatsby-theme-orga/src/templates/post-query.js``
から下記を除外してから build する

```
html
timeToRead
wordCount
```

ただ、 おそらく html をなくした影響で本文が表示されてなくなっていたり、途中までしかバグででていないっぽい
