# LeetCode-Notes
This repository serves as a reference for topics learned and explored on leetcode.com

Other great sites to challenge yourself:
* https://www.codingame.com/
* https://www.codewars.com/

Video notes can be found [here](https://docs.google.com/spreadsheets/d/1UDMgFw9MvjOi-yweHHejYZt6BvQaQWcDc-R-oKOJ2xA/edit#gid=0) for most popular problems. Awesome video contant can be found from [NeetCode](https://www.youtube.com/channel/UC_mYaQAE6-71rjSN6CeCA-g) as well.


## Chapters:
* Trees
* Graphs


## Trees

https://www.geeksforgeeks.org/tree-traversals-inorder-preorder-and-postorder/

https://leetcode.com/discuss/general-discussion/969327/Graph-Algorithms-One-Place-or-Dijkstra-or-Bellman-Ford-or-Floyd-Warshall-or-Prims-or-Kruskals-or-DSU

https://leetcode.com/discuss/general-discussion/937307/iterative-recursive-dfs-bfs-tree-traversal-in-pre-post-levelorder-views



For/in for Objects:
```
var person = {
   name: "Ben", 
   surname: "Bundy",
   age: 31,
};
var text = "";
var x;
for (x in person) {
   text += person[x];
}
```

For/of for strings and arrays:
```
var cars = ["Ferrari", "BMW", "Opel", "Mercedes"];
var text = "";
for (let car of cars) {
  text += car + "<br>";
}
```


## Tree Problems
Depth First Traversals: 
* Inorder (Left, Root, Right) : 4 2 5 1 3 
* Preorder (Root, Left, Right) : 1 2 4 5 3 
* Postorder (Left, Right, Root) : 4 5 2 3 1


