

## ideas
### idea-1 废弃
> 搜索到<https://github.com/BaronZ/StarProjects>，发现用issue的label管理star项目很方便，比这个idea方便。
> 所以此idea废弃
- 因为访问<https://app.astralapp.com/dashboard>(一个star管理的网站)突然访问不了了。所以希望有一个项目来分类整理我所star的项目。
- 想着在`readme.md`中用多级标题来分类star项目，但是很不方便，如果一个star项目属于多个标签，就不行。
- 开发一个脚本，可以整理github的star，希望支持多标签。
- 初步想法为一个文件列出所有tags，它们指向不同文件。如下
```
> readme.md内容：
## tags
### [tag1](tags/tag1.md)
### [tag2](tags/tag1.md)

>  tag1.md内容：
- https://github.com/yeasy/docker_practice
> 项目说明：xxx（这里项目说明会因为项目属于多个tag而重复，所以考虑要一个总的项目列表，列出所有项目，然后加上说明，这里只用指向项目列表的项目锚点链接即可。）
- xxx
- xxx

>  tag2.md内容：
- https://github.com/yeasy/docker_practice
> 项目说明：xxx
- yyy
- yyy
```
如果每次都手动维护，很麻烦，所以可以写一个脚本。



## 关键字
### idea1
star tag label
> 当需要写一个东西的时候，可以去Google/GitHub多搜索，可能他人有更好的想法，可以借鉴哦，**不要闭门造车**。