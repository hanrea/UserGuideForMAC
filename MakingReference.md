## 制作参考

本说明是制作帮助文档的规范说明，修改本文档前请详细阅读本文档，以及本文档提及的规范。
本说明是对cocos-docs制作要求的一个补充，用于适配Manual手册的制作。

目前本文档主要显示在两个地方，一个是Cocos官方文档[cocos-doc](https://github.com/chukong/cocos-docs/)，一个是在线帮助手册[Manual](manual.cocosstudio.org)。其中是cocos_doc是cocos引擎的统一文档管理仓库。作为Cocos文档的主要分支，它不仅包含了Cocos Studio 部分，还包括的Cocos 的引擎部分。另一个帮助手册是独立展示Cocos Studio帮助系统gitbook是用于制作电子书，相关信息可以在gitbook的官方查看，或者前往[Manual](manual.cocosstudio.org)体验。

###注意事项

如果您能看到本文档，说明你查看的是私人仓库地址，该仓库下的MakingReference.md、README.md、SUMMARY.md、SUMMARY_en.md四个文件仅保存于私人仓库内，请勿提交至[cocos-doc](https://github.com/chukong/cocos-docs/)


### 流程

本文档由于跟随Cocos Studio 版本发布，为了保证历史版本用户能够获取对应的帮助手册，需按照以下流程制作。[1.0正式版本发布之前可忽略]

#### 制作新版本
1. 打包
	开始一个新版本编辑前打包当前的主分支的内容，作为上一个版最终版本。打包应同时生成网页版本和pdf。将打包后的网页压缩为zip包，并添加下载链接至“other/contact_support”文档内。
2. 新增内容或修改内容
4. 更新[cocos-doc](https://github.com/chukong/cocos-docs/)导航地址
5. 提交[cocos-doc](https://github.com/chukong/cocos-docs/)、
6. 更新帮助手册网站[Manual](manual.cocostudio.org),目前该页面通过github Pages服务器托管。将编译出的页面替换即可。
7. 