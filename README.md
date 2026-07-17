<p align="center">
  <img src="./assets/logo.svg" width="96" alt="拾光 Logo">
</p>

<h1 align="center">拾光 · ReLight</h1>

<p align="center">为家庭整理熟悉的回忆与陪伴内容。</p>

## 关于拾光

「拾光」由两个相互配合的 iOS App 组成，帮助家属整理家庭照片、时光线索和经过授权的熟悉声音，并以更低操作复杂度呈现给家人。

- **拾光家属（iPhone）**：整理时光线索与家庭照片，设置内容偏好和回避项，管理经过授权的熟悉声音，并向家人端发布内容。
- **拾光相伴（iPad）**：以更大画面、更少层级呈现家属准备的家庭相册与声音内容。

当前上架版本不包含第三方影音网站、网页会话或外部视频播放功能。

## 产品原则

- **家属确认**：AI 可以协助理解、生成候选和组织内容，但家庭事实与呈现边界由家属确认。
- **低复杂度**：家人端减少层级、选择和突兀打断，让操作更简单、内容更稳定。
- **隐私与授权**：家庭照片、位置、人生线索和声音应获得适当授权；熟悉声音支持停用、授权撤回和删除请求。
- **不用于追踪**：产品不展示第三方广告，不将数据用于跨 App 追踪。
- **非医疗产品**：拾光不提供医疗诊断，不替代医生或专业照护建议，也不承诺治疗或延缓病程。

## 隐私与支持

本仓库的 `docs/` 目录提供 App Store 上架所需的公开页面：

- [产品与联系页面](docs/index.html)
- [隐私政策](docs/privacy.html)
- [技术支持](docs/support.html)
- [隐私选择与数据删除](docs/privacy-choices.html)

公开页面部署后将使用以下地址：

- https://flylow24.github.io/ReLight/
- https://flylow24.github.io/ReLight/privacy.html
- https://flylow24.github.io/ReLight/support.html
- https://flylow24.github.io/ReLight/privacy-choices.html

联系邮箱：xma.origin@gmail.com

## 数据处理摘要

家庭资料主要通过用户自己的 iCloud / CloudKit 私有数据库在设备间同步。用户主动使用相应智能整理或声音能力时，完成请求所需的部分照片缩略图、照片位置、家庭线索或授权声音样本可能通过开发者服务端及受托服务提供商处理。详细范围、用途、保存和删除方式以[隐私政策](docs/privacy.html)为准。

## 公开仓库边界

本仓库用于产品介绍、隐私与支持页面。产品源代码、部署配置、家庭数据和内部运维信息不在此公开。

请勿在 Issues、Discussions 或其他公开区域上传真实家庭照片、录音、身份信息、精确位置或健康资料。如需技术或隐私支持，请发送邮件至 xma.origin@gmail.com。
