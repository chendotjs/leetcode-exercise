承接上一题，递归算出每个节点左右子树的高度，做判断。但这样的从根计算，很多节点重复计算了...

在从根计算的同时，是不是可以用一个hashMap来存储每个子树的高度，后面只需要从hashMap里面取得。

还可以借鉴后序遍历的思想，从最底部开始计算。
