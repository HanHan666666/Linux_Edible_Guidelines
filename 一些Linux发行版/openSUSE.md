# openSUSE

openSUSE 是一个[社区主导](../%E4%B8%80%E4%BA%9B%E6%A6%82%E5%BF%B5/%E7%A4%BE%E5%8C%BA%E6%94%AF%E6%8C%81.md)的Linux发行版。使用[zypper](../%E4%B8%80%E4%BA%9B%E8%BD%AF%E4%BB%B6%E5%8C%85%E7%AE%A1%E7%90%86%E5%99%A8/rpm%E7%B3%BB/zypper.md)作为[包管理器](../%E4%B8%80%E4%BA%9B%E8%BD%AF%E4%BB%B6%E5%8C%85%E7%AE%A1%E7%90%86%E5%99%A8/%E8%BD%AF%E4%BB%B6%E5%8C%85%E7%AE%A1%E7%90%86%E5%99%A8.md)。  
> 同时它为商业用户提供了商业版SUSE Linux Enterprise Server (SLES)

---

## 下载链接

- 官网：[https://www.opensuse.org/](https://www.opensuse.org/)
- [开源镜像站](../%E4%B8%80%E4%BA%9B%E6%A6%82%E5%BF%B5/%E5%BC%80%E6%BA%90%E9%95%9C%E5%83%8F%E7%AB%99.md)：[https://opentuna.cn/opensuse/](https://opentuna.cn/opensuse/)

---

## 特性

### Tumbleweed

- [滚动式发行](../%E4%B8%80%E4%BA%9B%E6%A6%82%E5%BF%B5/%E6%BB%9A%E5%8A%A8%E5%BC%8F%E5%8F%91%E8%A1%8C.md)
- 友好的安装方式
- 强大的[snapper](../%E4%B8%80%E4%BA%9B%E5%BE%88%E6%9C%89%E7%94%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8C%85/snapper.md)回滚快照
- 虽然是社区支持的发行版，但它与商业版共享源代码。故用户可以得到近乎商业支持的BUG响应质量
- 有内核签名，可以开启Security Boot

### Leap

- 更贴近于商业版的代码
- 周期式更新，减少潜在的BUG
- 除以上两点，其他与Tumbleweed相同

## 不足

- [zypper](../%E4%B8%80%E4%BA%9B%E8%BD%AF%E4%BB%B6%E5%8C%85%E7%AE%A1%E7%90%86%E5%99%A8/rpm%E7%B3%BB/zypper.md)这个包管理器安装应用默认会安装所有可选依赖，但不会自动卸载孤立的依赖，导致系统臃肿
- 某些可选依赖的包被列为强依赖，导致系统臃肿

- 受限于德国的版权法，多媒体相关的大部分库被移除解码器，需要自己从第三方库[Packman]()

---

## 适用人群

- 已经体验过其他Linux发行版，对Linux有兴趣并想了解Linux各组件
- 愿意查询文档自己解决问题的极客Geek
- 想追随最新的Linux技术潮流

## 不适用人群

- 不接受繁琐的配置
- 追求稳定
- 希望开箱即用的体验
