# webOcr
WebOcr，基于Google Tessract4机器学习构建中英文离线Ocr项目。 在其基础上提供了http调用的接口，便于你在其他的项目中调用。 并且提供了Docker，便于部署。

# 特性
### 中文识别
快速高识别率

### 模型训练
通过jTessBoxEditor编辑器，进行模型样本训练，提高识别率

### 并发请求
由于模型本身不支持并发，但通过golang协程的方式，能支持一定数量的并发请求。具体并发数取决于机器的配置。
