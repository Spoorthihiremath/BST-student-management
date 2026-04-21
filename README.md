#  BST Student Management System 

##  Overview
This project demonstrates the application of **Binary Search Trees (BST)** in managing student records efficiently using the C programming language.

The program allows:
- Insertion of student IDs
- Searching for a student
- Displaying student IDs in sorted order

---

##  Scenario
In a college, each student is assigned a unique **Student ID**.  
Managing these records using arrays becomes inefficient as the data grows.

To solve this, we use a **Binary Search Tree (BST)** where:
- Smaller IDs are stored in the left subtree
- Larger IDs are stored in the right subtree

This ensures fast searching and automatic sorting of records.

---

##  Justification
Binary Search Tree is used because:
- It provides efficient **search, insert, and traversal**
- Maintains **sorted order automatically**
- Reduces time complexity compared to linear search
- Dynamic structure (no fixed size limitation)

---

##  Algorithm

### 🔹 Insertion
1. If root is NULL → create a new node  
2. If value < root → insert in left subtree  
3. If value > root → insert in right subtree  

### 🔹 Search
1. Compare key with root  
2. If equal → element found  
3. If smaller → search left  
4. If larger → search right  

### 🔹 Inorder Traversal
1. Traverse left subtree  
2. Visit node  
3. Traverse right subtree  

---

##  Time Complexity

| Operation   | Average Case | Worst Case |
|------------|-------------|-----------|
| Insertion  | O(log n)    | O(n)      |
| Search     | O(log n)    | O(n)      |
| Traversal  | O(n)        | O(n)      |

---


##  Code
The complete implementation is available in:
bst.c

---

---

##  Sample Input
Enter number of elements: 5  
Enter elements:  
10 5 20 3 7  
Enter element to search: 7  

---

##  Sample Output
Inorder Traversal: 3 5 7 10 20  
Element found  

---

## How to Run

1. Compile:
gcc bst.c -o bst

2. Run:
./bst

---

##  Conclusion
Binary Search Trees provide an efficient way to store, search, and sort data in real-world applications like student record management systems.

---

##  Author
Spoorthi Hiremath
USN 01FE24BEC262
