# 全景Beta50静态报告
HTML + 原生JavaScript + Pannellum

<directory>
results/ - 50份原尺寸PNG，字节与本地已核验成品一致
originals/ - 5张原图
sources/ - 原图轻量预览
previews/ - 50张已归档轻量预览
actual-prompts/ - 50项实际送模词
prompts/ - 10条件冻结词
vendor/ - Pannellum脚本、样式和许可
</directory>
<config>
index.html - 报告首页，与report.html同文
report.html - 筛选图库与完成状态
viewer.html - 原图/结果联动360
plan.json - 冻结配置
batch.json - 原50项身份
status.json - 静态50成功状态与本地预览路径
verification.json - 50份归档词/配置核验
materialization.json - 原件SHA和尺寸
rule.prompt.txt - 公共规则原文
recovery-public-results.json - 空恢复合并表
asset-manifest.json - 发布文件SHA/大小
.nojekyll - 静态目录直出
README.md - 报告范围
</config>

[PROTOCOL]: 变更时更新此头部，然后检查 CLAUDE.md
