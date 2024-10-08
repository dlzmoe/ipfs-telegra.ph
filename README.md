
# ⚛ IPFS telegra.ph clone

用于将数据发布到 IPFS 网络的极简发布工具。
ui克隆来自 [Telegra.ph](http://telegra.ph)

在输入文章标题和作者姓名之后，用户即可随意创作。我们发布文章之后，就能够获得这篇文章的独立网址。我们只需要将上面获得的文章链接发送给好友，就能够在浏览器打开文章来阅读。

# 特点
* 操作简洁
* 页面干净
* 无需登陆
* 支持图片、gif、mp4即时插入并预览
* 支持 Youtube 、Vimeo 外链和预览

# 部署 

将public上传到任意环境即可。

# ipfs上传接口

默认使用 localhost:5001 ，通过页面 location.hash 传递域名可以覆盖整个配置，例如 api.abc.com ,将会调用 api.abc.com/api/v0/add 上传数据。

# 环境变量

window.api_host 提交到ipfs的接口，可以只实现 /api/v0/add 

window.ipfs_gateway 发布成功后默认跳转的ipfs网关

# 样例

cid：QmTCrcy5gE85cwqQf2UdcYpjMb7PrWKqBBcAuHoCwcGXZ6

[blockframe](https://ipfs.blockframe.io/ipfs/QmTCrcy5gE85cwqQf2UdcYpjMb7PrWKqBBcAuHoCwcGXZ6/#cdn.ipfsscan.io)

[ipfs.io](https://ipfs.io/ipfs/QmTCrcy5gE85cwqQf2UdcYpjMb7PrWKqBBcAuHoCwcGXZ6/#cdn.ipfsscan.io)

你也可以自己下载ipfs-desktop ，访问 http://127.0.0.1:8080/ipfs/QmTCrcy5gE85cwqQf2UdcYpjMb7PrWKqBBcAuHoCwcGXZ6/

## Thanks
 * http://telegra.ph
