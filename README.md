HarmonicAlbum
=============

Building a Album that can get images automatically classified.

## 一、功能列表

1. 基本相册 按时间、文件夹、GPS等分类
2. 核心功能，基于图片内容自动分类。自动给多个相片贴多个标签。按标签分类   服务器端训练参数传到客户端，客户端执行分类
3. 老师需求：以小图搜大图CBIR
4. 云相册上传、备份 云服务
5. 通过分类标签搜索 颜色标签搜索、人脸搜索 TBIR
6. 在线编辑 美化、圈脸
7. 如做成商业化产品，可以往：社区分享 以图汇友发展，类Flickr，用高质量分析内容增加用户粘性、现金流



## 二、系统概要设计
1. 全端 B/C + S
2.   B/C 上传、展示、编辑
3.   S 存储、训练、贴标签
4. 大数据的传输+图片存储 + 高并发访问+scalable参考淘宝CDN



## 三、用到的技术
1. Origami、keynote
2. 以图搜图 [哈希感知](http://www.ruanyifeng.com/blog/2011/07/principle_of_similar_image_search.html)

## 四、调研
1. 标注更改、上传重新练的时间
2. 有没有好的Annotation Label Change的算法
3. 网易、百度、amazon相册对比评测


