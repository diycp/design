# 架构

![Architecture](https://www.lucidchart.com/publicSegments/view/55b4c3c8-f456-44a4-8283-83b5f0220a1c/image.png)

# 设计

- [x] 思考项目定位和用户故事
- [x] 思考和调研关键技术
- [x] 写开题报告
- [x] 绘制架构图

# 开发

## APP代码拆分与动态链接技术

- [x] 通过npm shrinkwrap来获得APP的依赖和其版本
- [x] 把依赖项打成单独的包
- [x] 去掉原本APP包中依赖项的代码
- [x] 在APP运行时动态链接依赖项
- [x] webpack插件，一键完成这些工作并生成tar.gz包
- [ ] 在较大的项目中尝试使用这种技术，确保稳定性

## 后端开发

- [x] 中央服务器接受新APP上传
- [ ] 中央服务器管理用户信息
- [ ] 中央服务器管理APP内支付
- [x] 中央APP仓库，管理APP、APP版本数据
- [x] 中央APP仓库，管理APP依赖项
- [x] 中央APP仓库，提供文件下载能力
- [x] 中央APP仓库，提供根据GPS位置发现APP
- [x] 镜像APP仓库（城市CDN或NAT内），提供根据列表发现APP
- [x] 镜像APP仓库和中央APP仓库的同步工具
- [ ] 使用DNS解析的方法让用户就近选择APP仓库


## 安卓客户端

- [ ] 在本地管理依赖库
- [ ] 在本地管理APP本身的代码和版本
- [ ] 在本地拼装与执行APP
- [ ] fork cordova来提供native接口调用（如扫码、GPS等能力）
- [ ] 调用根据GPS坐标发现APP的接口、在NAT内部发现APP列表
- [ ] 一键启动APP的桌面小工具 
- [ ] 用户信息管理和授权给APP
- [ ] 通过签名来实现APP内支付授权

## DEMO APP开发

- [ ] 停车场缴费
- [ ] 餐厅点菜
- [ ] 校车时刻表

## 论文和答辩

- [ ] 论文书写