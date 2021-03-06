<p align="center"><a href="https://github.com" target="_blank" rel="noopener noreferrer"><img width="100" src="https://avatars1.githubusercontent.com/u/8307075?s=460&v=4" alt="Github logo"></a></p>
<p align="center"><a href="https://travis-ci.org" target="_blank" rel="noopener noreferrer"><img src="https://travis-ci.org/RUSHUI/Karam-exercise.svg?branch=master" alt="CI status"></a></p>

### 安装

* 全局安装 karma

```
npm install -g karma-cli
```

* Fork 代码仓库并拉到本地
* 安装所有依赖

```
npm install
```

* 初始化测试

```
karma init
```
    1. Which testing framework do you want to use ? (mocha)
    2. Do you want to use Require.js ? (no)
    3. Do you want to capture any browsers automatically ? (Chrome)
    4. What is the location of your source and test files ? (https://cdn.bootcss.com/jquery/2.2.4/jquery.js, node_modules/should/should.js, test/**.js)
    5. Should any of the files included by the previous patterns be excluded ? ()
    6. Do you want Karma to watch all the files and run the tests on change ? (yes)

* 启动测试

```
karma start
```

* 查看 `./test/test.js` 测试用例写法 

* 提交github，尝试接入Travis CI

### 参考

* [karma](http://karma-runner.github.io/)
* [jQuery 中文文档](http://jquery.cuishifeng.cn/)
