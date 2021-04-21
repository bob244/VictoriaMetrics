# VictoriaMetrics

VictoriaMetrics是一个优化非常好的 prometheus替代品。
其中的vmalert是把prometheus的manager给单独出来
但是一样有本地化配置的尿性。
能力有效，抄抄弄弄新增一个参数 -ruleurl （get）
可以从远程http得到配置，方便做界面化配置。
和文件的rule 不冲突，会进行合并
