
# Binary trees

and the three ways to go through them: pre-order, order, re-order. In this task the goal is to realize a binary tree with possible iterators to go through it in all three arrangements.

Department Name: BinaryTree. Methods required:
* `add_root` - receives one input and places it at the root of the tree, If there is already something in the root, it is replaced.
* `add_left` - Receives two inputs: The first input indicates something that already exists in the tree, The second input indicates something new to be added as his left child (if he already has a left child - his content should be replaced).
* `add_right` - Same as above, only the extension is as the right child.
* `begin_preorder` (), * `end_preorder` () - Returns iterators to move in order of preorder (parent - left - right).
* `begin_inorder` (), * `end_inorder` () - Returns iterators to move in order in order (left - parent - right).
* `begin_postorder` (), * `end_postorder` () - Returns iterators for switching in order order (left - right - parent).
* `Output operator` - prints the Tree in logical format.

More Details:

* The tree is not necessarily arranged in ascending order, nor is it balanced.
* The order of the data in the tree is according to the way they are inserted.
* In add_left, add_right functions, if the first input does not exist in the tree - an exception must be thrown. If it exists twice or more - choose one of the two options and add   there (in the automatic tests do not enter such situations, so that the result will be unambiguous).

