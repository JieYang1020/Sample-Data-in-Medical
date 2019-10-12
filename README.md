# Sample-Data-in-Medical
some sample data for "Causality Extraction for Medical Literature"
数据中发现的课题难点
1. 指代问题:their, it指谁(多头注意力机制解决)
2. 一整句为因或果
3. 考虑因果顺序(有的论文只是将因果抽取出来，并未考虑到两者顺序)
4. and also等连接词增长了和第一个因/果的距离
5. 否定性因果关系：A和B没有因果关系
6. A对B有negative effects，但具体是什么果没说
7. 隐喻因果关系
8. 多种链式关系：A和B分别导致C和D；A导致B，B导致C；A导致B和C
9. 顺序或层级关系：A导致B和C，是同时导致还是先导致B，接着导致C？
10. 一个句子含有cause等关键词，但不一定是因果关系
11. 因果关系属于一个长句的一小部分，不好抽取
12. 长句子抽取问题
13. cause by, ..by 第二个by连接很前面的一个cause
