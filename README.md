# Enriching-Pre-trained-Language-Model-with-Entity-Information-for-Relation-Classification
论文复现
复现召回率为82%左右，尚未达到论文中的89%，目前尚未找到原因，欢迎交流想法。
工具：pytorch


代码重新修改：
1.只考虑了实体的信息，F1-score_macro=85.79%
2.考虑了实体和特殊tokens的vector,F1-score-macro=86,16%
