# A Hitchiker's guide to guides

Learning markdown is an exersize as much in learning what you _**can**_ do, as much as what you _**cannot**_ do. 
In this assignment we are to look at five different guides or tutorials on markdown and how to use the different functions. 

The guides I will pull from are 

* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Guide to Markdown](https://blog.ghost.org/markdown/)
* [Daring Fireball](https://daringfireball.net/projects/markdown/syntax)
* [My Brother]()

## Mastering Markdown

Each of these tutorials or pages have a decent amount of overlap but this one stands out as a repository for commands. 
I can scroll through and visually find what it is I need to do and then read after I've found it. 

For example, if I needed to know how to show highlighting syntax so that more experienced users in other langauges can better 
see and mentally decode a code block I could scroll and find a visual aid without much effort. 

One example such as this,


```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Markdown Cheatsheet

Cheatsheet much like Mastering Markdown is easy to use due to visual cues. However cheat sheet goes into more detail once 
you've found the instructions you're looking for. Even going so far as to add multipule examples of how to do something.
There are also suggestions on how to do something via HTML if Markdown doesn't allow for it. 

An example of this would be when they talk about resizing images while working with youtube videos. 
``` 
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```
## Guide to Markdown

