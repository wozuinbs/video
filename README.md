# VIDEO

##### 在线观看：
##### http://meinu.ml/          
##### https://wozuinbs.github.io/video/
##### TG: @wishTestJoin_bot



## GitHub API  获取仓库目录

#####  基地址：`https://api.github.com`

### 默认前1k个文件

```
GET /repos/{owner}/{repo}/contents/{path}

owner：所有者
repo：仓库名字
path：路劲
```

### 全部文件

```
GET /repos/{owner}/{repo}/git/trees/{tree_sha}

owner：所有者
repo：仓库名字
tree_sha：目录的sha值,可以通过上面的接口拿到
```



## jsDelivr CDN加载仓库文件

```
https://cdn.jsdelivr.net/gh/{username}/{仓库名字}/{path}
```

```
https://cdn.jsdelivr.net/gh/wozuinbs/video/....
```



## 文件目录

### /

```
https://api.github.com/repos/wozuinbs/video/contents
```

### /mini

```
https://api.github.com/repos/wozuinbs/video/contents/mini
```

```
https://api.github.com/repos/wozuinbs/video/git/trees/30450e11171827542c972cf1568369b6f9a2ea6b
```

```
https://cdn.jsdelivr.net/gh/wozuinbs/video/mini/{fileName}
```

### /big

```
https://api.github.com/repos/wozuinbs/video/contents/big
```

```
https://cdn.jsdelivr.net/gh/wozuinbs/video/big/{folder}/index.m3u8
```

​        *big为 `m3u8 `视频，一个目录一个文件，索引为 `*/index.m3u8`*

### /m3u8

######    因为某些原因仓库丢失了，clone不下来，大文件干脆重新创建一个规定。`/m3u8/index/` 为索引目录, `/m3u8/data/` 为每个文件的ts切片

```
https://api.github.com/repos/wozuinbs/video/contents/m3u8/index
```

```
https://cdn.jsdelivr.net/gh/wozuinbs/video/m3u8/index/{fileName}
```



**数据来自互联网抓取，如有侵犯请提交  `lssues`**

