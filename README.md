ZGJM

### 提交代码

```
git push --set-upstream coding master
git push --set-upstream origin master
```

### Hugo

#### 1. 安装

```
brew install hugo

hugo version

```

#### 2. 写文章

```
hugo new posts/my-first-post.md
```

#### 3. 生成

```
hugo -D
```

#### 3. 预览（带生成）

```
hugo server -D

```

#### 4. Search

使用Algolia：

https://10101.io/2018/11/23/search-with-algolia-in-hugo

```npm
npm init  // 初始化，不懂具体内容一路回车就好
npm install atomic-algolia --save
npm run algolia
```
