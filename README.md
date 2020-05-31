# PatchyVideo/i18n

PatchyVideo 翻译计划 / PatchyVideo Translation Project

这是 PatchyVideo 的静态语言文件库，存放 PatchyVideo 各个项目的静态语言文件，同时欢迎贡献本库。

## 贡献翻译

你想看到某个语言的 PatchyVideo 吗？我们需要帮助！

贡献翻译十分简单：

1. Fork 并 Clone 这个库。
2. 在对应的语言中查找你想翻译的项目和条目，如不存在可以参照 CHS（默认语言） 创建。
3. Commit 并提交 Pull Request。
4. 等待项目同步并部署。

建议提交前先测试翻译是否正常，各个项目的测试方法已在对应的 README 中给出。

## Commit comment 格式

Comment 格式为 “📖/📘 \[项目\]说明”。

如：📖 \[patchyvideo-vue\]Complete the translation of HomeMain

若项目的所有条目未全部翻译完毕，最前的书图标应为打开状态，让后来者了解翻译进度。
若未满足格式 Maintainer 会适当修改。

## 各项目的语言文件说明

### patchyvideo-vue

#### 格式

所有语言为自动载入，每个语言文件与对应的组件对应。

如：/src/components/homecompoents/HomeMain.vue 的词条对应在 /src/components/homecompoents/HomeMain.json

此外有部分词条在 _common.json 中，为所有组件通用。如有需要分离的词条请在这里提交 issue。

#### Utils

提供一个 i18n 命令，具体请通过 npm run i18n 查看
