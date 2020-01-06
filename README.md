# Kooboo 优化版monaco

## 构建步骤
1. 运行此仓库的prepublishOnly生成release目录
2. 下载microsoft/monaco-editor，并安装依赖
3. 将此仓库生成的release目录拷贝到microsoft/monaco-editor的\node_modules\monaco-html进行覆盖
4. 运行microsoft/monaco-editor的release
5. 将microsoft/monaco-editor生成的release目录中的\min\vs目录拷贝到此仓库的vs目录进行替换