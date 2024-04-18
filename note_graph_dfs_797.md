# error
## 终止条件
```cpp
if (n==graph.size()-1) {//graph[n].size()==0
```
遍历到最后一个节点，或者说是目标节点
而不是遍历到空节点(类似叶子节点)

## 终止条件
```cpp
dfs(graph, graph[n][i]); //n + 1
```
递归是递归链接该节点的其他节点，也就是graph[n][i]但是写成n+1就难蹦
