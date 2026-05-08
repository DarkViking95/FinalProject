# FinalProject
Thursday, May 7 11:59 p.m.
Final Project
By: Ethan Bohling

Functions done:
shared_ptr<Node> persistentBST::getMin(shared_ptr<Node> node);
shared_ptr<Node> persistentBST::deleteNode(shared_ptr<Node> node, int key);
persistentBST persistentBST::remove(int key);

VersionEntry FatNode::getVersion(int ver);
shared_ptr<FatNode> FatPersistentBST::insertFat(shared_ptr<FatNode> node, int key, int ver);
int FatPersistentBST::insert(int key);
void FatPersistentBST::inorder(int ver);

Stream<T> reverseConcat(Stream<T> front, Stream<T> rear, Stream<T> acc);
lazyPersistentQueue lazyPersistentQueue::balance();
lazyPersistentQueue lazyPersistentQueue::enqueue(T x);
lazyPersistentQueue lazyPersistentQueue::dequeue();
T lazyPersistentQueue::peek();

How to compile/run program
To compile: type make in terminal
To run: type ./p_bst_1 for p_bst_1.cpp
To run: type ./p_bst_fat for p_bst_fat.cpp
To run: type ./p_queue_lazy for p_queue.cpp
