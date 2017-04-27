# 北上见面会

---

- 这个项目为微信群好友北京见面会创建，旨在加强世界各地友好交流，发扬中华团结友爱文化。

- 这是一个开放的时代，全民交友的时代终将到来，人与人间的距离会变的越来越近。

- 这是一个娱乐的时代，正如伟大开源先驱`Linus`在他的书`Just For Fun`中所说的，这个世界最终会朝着娱乐的终极目标发展。


<p align="right">王志舟</p>

<p align="right">2017年4月27日 于 北京</p>

<p align="right">QQ: 824219521</p>

<p align="right">WeChat: w_z_z_1991</p>


---

# 项目合作方式

## 安装`MKDocs`熟悉使用方式
	
**MKDocs快速入门:** <http://www.mkdocs.org>

## 克隆仓库

```
git clone https://github.com/wangzhizhou/BSMeeting.git
```

## 修改并本地运行测试 

启动本地`http`服务，查看文档效果

```
joker@localhost:~/Desktop $ cd BSMeeting/
joker@localhost:~/Desktop/BSMeeting $ mkdocs serve
INFO    -  Building documentation... 
INFO    -  Cleaning site directory 
[I 170427 23:34:58 server:283] Serving on http://127.0.0.1:8000
[I 170427 23:34:58 handlers:60] Start watching changes
[I 170427 23:34:58 handlers:62] Start detecting changes
```
**浏览器打开`http://127.0.0.1:8000`查看文档**

<br/>

* 提交并发起合并请求

* 项目已设置`Web Hook`自动发起`Read The Docs`文档构建，主仓库每次改动或合并后会自动构建新版文档

* 项目文档地址: <http://bsmeeting.readthedocs.io/zh/latest/?>

<br/>

### 工程目录结构

```
BSMeeting/
├── LICENSE      //遵守的许可证
├── README.md    //项目介绍
├── docs         //文档目录，使用Markdown语法编写
│   ├── deal.md
│   ├── group.md
│   ├── index.md
│   ├── ktv.md
│   ├── maillist.md
│   ├── restaurant.md
│   ├── route.md
│   └── video.md
└── mkdocs.yml  //文档配置文件

1 directory, 11 files
```

