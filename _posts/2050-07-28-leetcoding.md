---
layout: post
title: "Leetcoding"
date: 2021-08-09
excerpt: "My solutions to Leetcode problems"
tags: [python, java, coding, leetcode, algorithm, data structure, interview]
comments: true
---

> **Sharing my solutions that I post on my [GitBook](https://yyloumike.gitbook.io/leetcode/){:target="_blank"} and [GitHub](https://github.com/yylou/leetcode){:target="_blank"} to the [LeetCode](https://leetcode.com/){:target="_blank"} problems. If you find it helps, please do not hesitate to give me a STAR!**

<!-- 
| [](){:target="_blank"}
| [****](){:target="_blank"}
-->

| Problem / Solution | Level | Tag | Time / Mem (%) |
|:-------------------|:------|----:|---------------:|
| [0001. 2 Sum](https://yyloumike.gitbook.io/leetcode/mixed/two-sum-4-qs/0001.-two-sum){:target="_blank"}                                                                   | Easy | Two Pointers | 94 / 79 |
| [0002. Add Two Numbers](https://yyloumike.gitbook.io/leetcode/linked-list/0002.-add-two-numbers){:target="_blank"}                                                        | Medium | Linked List | 94 / 45 |
| [**0003. Longest Substring Without Repeating Characters**](https://yyloumike.gitbook.io/leetcode/sliding-window/0003.-longest-substring-without-repeating-characters){:target="_blank"} | Medium | Sliding Window | 100 / 73 |
| [**0004. Median of Two Sorted Arrays**](https://yyloumike.gitbook.io/leetcode/binary-search/0004.-median-of-two-sorted-arrays){:target="_blank"}                          | Hard | Binary Search | 98 / 81 |
| [**0005. Longest Palindromic Substring**](https://yyloumike.gitbook.io/leetcode/dp/0005.-longest-palindromic-substring){:target="_blank"}                                 | Medium | DP | 99 / 93 |
| [0021. Merge Two Sorted Lists](https://yyloumike.gitbook.io/leetcode/linked-list/0021.-merge-two-sorted-lists){:target="_blank"}                                          | Easy | Linked List | 99 / 88 |
| [**0023. Merge k Sorted Lists**](https://yyloumike.gitbook.io/leetcode/linked-list/0023.-merge-k-sorted-lists){:target="_blank"}                                          | Hard | Divide and Conquer | 99 / 39 |
| [**0028. Implement strStr()**](https://yyloumike.gitbook.io/leetcode/string/0028.-implement-strstr){:target="_blank"}                                                     | Easy | KMP | 97 / 100 |
| [0035. Search Insert Position](https://yyloumike.gitbook.io/leetcode/binary-search/0035.-search-insert-position){:target="_blank"}                                        | Easy | Binary Search | 92 / 23 |
| [**0038. Count and Say**](https://yyloumike.gitbook.io/leetcode/string/0038.-count-and-say){:target="_blank"}                                                             | Medium | String | 96 / 75 |
| [**0053. Maximum Subarray**](https://yyloumike.gitbook.io/leetcode/dp/0053.-maximum-subarray){:target="_blank"}                                                           | Easy | DP | 97 / 72 |
| [0067. Add Binary](https://yyloumike.gitbook.io/leetcode/string/0067.-add-binary){:target="_blank"}                                                                       | Easy | String | 91 / 53 |
| [0069. Sqrt(x)](https://yyloumike.gitbook.io/leetcode/binary-search/0069.-sqrt-x){:target="_blank"}                                                                       | Easy | Binary Search | 96 / 98 |
| [**0072. Edit Distance**](https://yyloumike.gitbook.io/leetcode/dp/0072.-edit-distance){:target="_blank"}                                                                 | Hard | DP | 98 / 84 |
| [0075. Sort Colors](https://yyloumike.gitbook.io/leetcode/two-pointer/0075.-sort-colors){:target="_blank"}                                                                | Medium | Two Pointers | 93 / 99 |
| [**0088. Merge Sorted Array**](https://yyloumike.gitbook.io/leetcode/two-pointer/0088.-merge-sorted-array){:target="_blank"}                                              | Easy | Two Pointers | 98 / 95 |
| [**0094. Binary Tree Inorder Traversal**](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0094.-binary-tree-inorder-traversal){:target="_blank"}    | Easy | Tree Traversal | 99 / 99 |
| [**0098. Validate BST**](https://yyloumike.gitbook.io/leetcode/tree/0098.-validate-binary-search-tree){:target="_blank"}                                                  | Medium | Binary Search Tree | 95 / 95 |
| [0100. Same Tree](https://yyloumike.gitbook.io/leetcode/tree/0100.-same-tree){:target="_blank"}                                                                           | Easy | Tree Traversal | 99 / 60 |
| [**0102. Binary Tree Level Order Traversal**](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0102.-binary-tree-level-order-traversal){:target="_blank"} | Medium | Tree Traversal | 100 / 69 |
| [0104. Maximum Depth of Binary Tree](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0104.-maximum-depth-of-binary-tree){:target="_blank"}          | Easy | Tree Traversal | 95 / 92 |
| [**0108. Convert Sorted Array to Binary Search Tree**](https://yyloumike.gitbook.io/leetcode/tree/convert-to-bst-2-qs/0108.-convert-sorted-array-to-binary-search-tree){:target="_blank"} | Easy | Binary Search Tree | 98 / 78 |
| [**0109. Convert Sorted List to Binary Search Tree**](https://yyloumike.gitbook.io/leetcode/tree/convert-to-bst-2-qs/0109.-convert-sorted-list-to-binary-search-tree){:target="_blank"} | Medium | Binary Search Tree | 99 / 58 |
| [**0110. Balanced Binary Tree**](https://yyloumike.gitbook.io/leetcode/tree/0110.-balanced-binary-tree){:target="_blank"}                                                 | Easy | DFS | 100 / 88 |
| [0111. Minimumm Depth of Binary Tree](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0111.-minimum-depth-of-binary-tree){:target="_blank"}         | Easy | Tree Traversal | 99 / 94 |
| [0121. Best Time to Buy/Sell Stock](https://yyloumike.gitbook.io/leetcode/dp/buy-and-sell-stock/0121.-best-time-to-buy-and-sell-stock){:target="_blank"}                  | Easy | DP | 96 / 61 |
| [0122. Best Time to Buy/Sell Stock II](https://yyloumike.gitbook.io/leetcode/dp/buy-and-sell-stock/0122.-best-time-to-buy-and-sell-stock-ii){:target="_blank"}            | Easy | DP / Greedy | 75 / 22 |
| [**0123. Best Time to Buy/Sell Stock III**](https://yyloumike.gitbook.io/leetcode/dp/buy-and-sell-stock/0123.-best-time-to-buy-and-sell-stock-iii){:target="_blank"}      | Hard | DP | 50 / 46 |
| [0144. Binary Tree Preorder Traversal](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0144.-binary-tree-preorder-traversal){:target="_blank"}      | Easy | Tree Traversal | 100 / 95 |
| [**0145. Binary Tree Postorder Traversal**](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0145.-binary-tree-postorder-traversal){:target="_blank"}| Easy | Tree Traversal | 99 / 92 |
| [**0148. Sort List**](https://yyloumike.gitbook.io/leetcode/sorting/0148.-sort-list){:target="_blank"}                                                                    | Medium | Sort | 98 / 96 |
| [0151. Reverse Words in a String](https://yyloumike.gitbook.io/leetcode/string/0151.-reverse-words-in-a-string){:target="_blank"}                                         | Medium | String | 100 / 43 |
| [0167. Two Sum II - Input array is sorted](https://yyloumike.gitbook.io/leetcode/mixed/two-sum-4-qs/0167.-two-sum-ii-input-array-is-sorted){:target="_blank"}             | Easy | Two Pointers | 96 / 32 |
| [**0170. Two Sum III - Data structure design**](https://yyloumike.gitbook.io/leetcode/mixed/two-sum-4-qs/0170.-two-sum-iii-data-structure-design){:target="_blank"}       | Easy | Binary Search | 100 / 86 |
| [**0188. Best Time to Buy/Sell Stock IV**](https://yyloumike.gitbook.io/leetcode/dp/buy-and-sell-stock/0188.-best-time-to-buy-and-sell-stock-iv){:target="_blank"}        | Hard | DP | 96 / 98 |
| [**0200. Number of Islands**](https://yyloumike.gitbook.io/leetcode/dfs-bfs/0200.-number-of-islands){:target="_blank"}                                                    | Medium | BFS / DFS | 94 / 95 |
| [0206. Reverse Linked List](https://yyloumike.gitbook.io/leetcode/linked-list/0206.-reverse-linked-list){:target="_blank"}                                                | Easy | Two Pointers | 99 / 80 |
| [**0215. Kth Largest in Array**](https://yyloumike.gitbook.io/leetcode/sorting/0215.-kth-largest-in-array){:target="_blank"}                                              | Medium | Sort / QuickSelect | 98 / 95 |
| [0226. Invert Binary Tree](https://yyloumike.gitbook.io/leetcode/tree/0226.-invert-binary-tree){:target="_blank"}                                                         | Easy | Binary Search Tree | 100 / 90 |
| [**0250. Count Univalue Subtrees**](https://yyloumike.gitbook.io/leetcode/tree/0250.-count-univalue-subtrees){:target="_blank"}                                           | Medium | DFS | 99 / 72 |
| [0278. First Bad Version](https://yyloumike.gitbook.io/leetcode/binary-search/0278.-first-bad-version){:target="_blank"}                                                  | Easy | Binary Search | 95 / 74 |
| [0283. Move Zeroes](https://yyloumike.gitbook.io/leetcode/two-pointer/0283.-move-zeroes){:target="_blank"}                                                                | Easy | Two Pointers | 97 / 74 |
| [0309. Best Time to Buy/Sell Stock with Cooldown](https://yyloumike.gitbook.io/leetcode/dp/buy-and-sell-stock/0309.-best-time-to-buy-and-sell-stock-with-cooldown){:target="_blank"} | Medium | DP | 96 / 39 |
| [0344. Reverse String](https://yyloumike.gitbook.io/leetcode/string/0344.-reverse-string){:target="_blank"}                                                               | Easy | String | 98 / 58 |
| [0367. Valid Perfect Square](https://yyloumike.gitbook.io/leetcode/binary-search/0367.-valid-perfect-square){:target="_blank"}                                            | Easy | Binary Search | 96 / 68 |
| [**0410. Split Array Largest Sum**](https://yyloumike.gitbook.io/leetcode/binary-search/0410.-split-array-largest-sum){:target="_blank"}                                  | Hard | Binary Search | 92 / 65 |
| [0415. Add Strings](https://yyloumike.gitbook.io/leetcode/string/0415.-add-strings){:target="_blank"}                                                                     | Easy | String | 97 / 83 |
| [0429. N-ary Tree Level Order Traversal](https://yyloumike.gitbook.io/leetcode/tree/n-ary-tree-traversal-3-qs/0429.-n-ary-tree-level-order-traversal){:target="_blank"}   | Medium | Tree Traversal / Stack | 99 / 97 |
| [0445. Add Two Numbers II](https://yyloumike.gitbook.io/leetcode/linked-list/0445.-add-two-numbers-ii){:target="_blank"}                                                  | Medium | Linked List | 97 / 90 |
| [0557. Reverse Words in a String III](https://yyloumike.gitbook.io/leetcode/string/0557.-reverse-words-in-a-string-iii){:target="_blank"}                                 | Easy | String | 93 / 11 |
| [0559. Maximum Depth of N-ary Tree](https://yyloumike.gitbook.io/leetcode/tree/n-ary-tree-traversal-3-qs/0559.-maximum-depth){:target="_blank"}                           | Easy | Tree Traversal / Stack | 94 / 47 |
| [0589. N-ary Tree Preorder Traversal](https://yyloumike.gitbook.io/leetcode/tree/n-ary-tree-traversal-3-qs/0589.-n-ary-tree-preorder-traversal){:target="_blank"}         | Easy | Tree Traversal / Stack | 99 / 76 |
| [0590. N-ary Tree Postorder Traversal](https://yyloumike.gitbook.io/leetcode/tree/n-ary-tree-traversal-3-qs/0590.-n-ary-tree-postorder-traversal){:target="_blank"}       | Easy | Tree Traversal / Stack | 99 / 95 |
| [**0653. Two Sum IV - Input is a BST**](https://yyloumike.gitbook.io/leetcode/mixed/two-sum-4-qs/0653.-two-sum-iv-input-is-a-bst){:target="_blank"}                       | Easy | Binary Search Tree | 93 / 77 |
| [**0654. Maximum Binary Tree**](https://yyloumike.gitbook.io/leetcode/tree/0654.-maximum-binary-tree){:target="_blank"}                                                   | Medium | Binary Tree / Stack | 100 / 65 |
| [0704. Binary Search](https://yyloumike.gitbook.io/leetcode/binary-search/0704.-binary-search){:target="_blank"}                                                          | Easy | Binary Search | 92 / 68 |
| [0714. Best Time to Buy/Sell Stock with Transaction Fee](https://yyloumike.gitbook.io/leetcode/dp/buy-and-sell-stock/0714.-best-time-to-buy-and-sell-stock-with-transaction-fee){:target="_blank"} | Medium | DP | 75 / 99 |
| [0875. Koko Eating Bananas](https://yyloumike.gitbook.io/leetcode/binary-search/0875.-koko-eating-bananas){:target="_blank"}                                              | Medium | Binary Search | 98 / 87 |
| [**0912. Sort an Array**](https://yyloumike.gitbook.io/leetcode/sorting/0912.-sort-an-array){:target="_blank"}                                                            | Medium | Sort | 91 / 51 |
| [0953. Verifying an Alien Dictionary](https://yyloumike.gitbook.io/leetcode/string/0953.-verifying-an-alien-dictionary){:target="_blank"}                                 | Easy | String | 96 / 91 |
| [0993. Cousins in Binary Tree](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/0993.-cousins-in-binary-tree){:target="_blank"}                      | Easy | Tree Traversal | 98 / 97 |
| [**1011. Capacity To Ship Packages Within D Days**](https://yyloumike.gitbook.io/leetcode/binary-search/1011.-capacity-to-ship-packages-within-d-days){:target="_blank"}  | Medium | Binary Search | 80 / 94 |
| [1302. Deepest Leaves Sum](https://yyloumike.gitbook.io/leetcode/tree/binary-tree-traversal-3-qs/1302.-deepest-leaves-sum){:target="_blank"}                              | Medium | Tree Traversal | 98 / 90 |
{: rules="groups"}
