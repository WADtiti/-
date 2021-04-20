# lightGBM
## Exclusive Feature Bundling（EFB）
假如feature间是exclusive的，我们可以bundle这些exclusive features.为了寻求一个尚可的bundle集合，我们把原问题转化为graph coloring问题,将feature作为点添加进去，且给并不exclusive的两点间加边。
### 补充：
graph coloring问题：图中有边相连的两点的着色不可以一样(In its simplest form, it is a way of coloring the vertices of a graph such that no two adjacent vertices are of the same color)
