## Install

If you don't have hexo, install hexo first:

``` bash
$ npm install hexo-cli -g
```

Install dependencies:
``` bash
$ git clone git@github.com:sysu-2014-cas/sysu-2014-cas.github.io.git
$ cd sysu-2014-cas.github.io
$ npm install
$ git clone https://github.com/iissnan/hexo-theme-next themes/next
```

## Writing

To create a new post with a title `title`:

``` bash
$ hexo new post title
```

Edit `source\_posts\YYYY-MM-DD-title.md` to write your post.

## Generate and deploy

Generate:

``` bash
$ hexo generate
```

Run server:

``` bash
$ hexo server
```

Deploy

``` bash
$ hexo deploy
```
