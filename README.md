# PatchyVideo/i18n

PatchyVideo 翻译计划 / PatchyVideo Translation Project

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

## 各项目的语言格式

### patchyvideo-vue

所有语言为自动载入，每个语言文件与对应的组件对应。

如：/src/components/homecompoents/HomeMain.vue 的词条对应在 /src/components/homecompoents/HomeMain.json
