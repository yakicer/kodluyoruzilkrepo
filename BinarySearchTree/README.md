# BINARY SEARCH TREE

## Creating Binary Search Tree Steps of Given Array 

### Consider an example: {7, 5, 1, 8, 3, 6, 0, 9, 4, 2}

#### **Explanation of Steps**
---

- First, we have to insert **7** into the tree as the root of the tree.
- Then, read the next element; if it is smaller than the root node, insert it as the root of the left subtree, and move to the next element.
- Otherwise, if the element is larger than the root node, then insert it as the root of the right subtree.

---
### Now, let's see the process of creating the Binary search tree using the given data element. The process of creating the BST is shown below

#### Step 1 - Insert 7
***
![Step 1](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST1.gif "Step 1")

#### Step 2 - Insert 5
***
As **5** is smaller than **7**, so insert it as the root node of the left subtree.

![Step 2](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST2.gif "Step 2")

#### Step 3 - Insert 1
***
**1** is smaller than **7** and **5**, so it will be inserted as a left subtree of **5**.

![Step 3](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST3.gif "Step 3")

#### Step 4 - Insert 8
***
As **8** is greater than **7**, so insert it as the root node of the right subtree.

![Step 4](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST4.gif "Step 4")

#### Step 5 - Insert 3
***
**3** is smaller than **7** and **5** but greater than **1**, so it will be inserted as the right subtree of **1**.

![Step 5](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST5.gif "Step 5")

#### Step 6 - Insert 6
***
**6** is smaller than **7** but greater than **5**, so it will be inserted as the right subtree of **5**.

![Step 6](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST6.gif "Step 6")

#### Step 7 - Insert 0
***
**0** is smaller than **7** , **5**, and **1** so it will be inserted as a left subtree of **1**.

![Step 7](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST7.gif "Step 7")

#### Step 8 - Insert 9
***
As **9** is greater than **7** and **8** so it will be inserted as the right subtree of **8**.

![Step 8](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST8.gif "Step 8")

#### Step 9 - Insert 4
***
**4** is smaller than **7** and **5** but greater than **1** and **3**, so it will be inserted as the right subtree of **3**.

![Step 9](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST9.gif "Step 9")

#### Step 10 - Insert 2
***
**2** is smaller than **7** and **5** but greater than **1**. Hence it is smaller than **3** it will be inserted as the left subtree of **3**.

![Step 10](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BST10.gif "Step 10")

### Now, the creation of binary search tree is completed. The complete tree is shown below
***

![Complete Tree](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/BinarySearchTree/assets/BSTComplete.png "Complete Tree")