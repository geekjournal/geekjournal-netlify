# Put some documentation here

$ hugo 


Thought about using staticman for comments, but using Disqus

from root Geekjournal director

`hugo new post/name-of-title-of-post.md`
Then edit the markdown, then
`hugo server -D` 
Then check localhost:1313 and make sure new content looks good, then
```
hugo undraft ./content/post/name-of-title-of-post.md
git add .
git commit -m "adding new content"
git push -u origin master
```
