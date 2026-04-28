

---

# 📘 Linked List Introduction

This repository provides a comprehensive introduction to **Linked Lists**, one of the most fundamental data structures in computer science. It explains core concepts, compares linked lists with arrays, and discusses their advantages, disadvantages, and real-world relevance.

📄 **Source Material:**
👉 

---

## 📌 Table of Contents

* [What is a Linked List?](#-what-is-a-linked-list)
* [Properties of Linked List](#-properties-of-linked-list)
* [Linked List ADT Operations](#-linked-list-adt-operations)
* [Why Linked Lists?](#-why-linked-lists)
* [Arrays Overview](#-arrays-overview)
* [Advantages of Arrays](#-advantages-of-arrays)
* [Disadvantages of Arrays](#-disadvantages-of-arrays)
* [Dynamic Arrays](#-dynamic-arrays)
* [Advantages of Linked Lists](#-advantages-of-linked-lists)
* [Disadvantages of Linked Lists](#-disadvantages-of-linked-lists)
* [Comparison: Linked List vs Array](#-comparison-linked-list-vs-array)
* [Conclusion](#-conclusion)

---

## 🔹 What is a Linked List?

A **Linked List** is a linear data structure used to store a collection of elements dynamically.

Unlike arrays:

* It **does not require contiguous memory allocation**
* It **can grow or shrink dynamically**

Each element (called a **node**) contains:

* **Data**
* **Reference (pointer)** to the next node

📌 Key idea:

> The last node points to `NULL`, and the entry point is called the **head**. 

---

## 🔹 Properties of Linked List

* Elements are connected using **pointers**
* The last node points to **NULL**
* Size is **dynamic**
* Memory is allocated **on demand**
* Efficient memory usage (no preallocation)

---

## 🔹 Linked List ADT Operations

### ✅ Main Operations

* **Insert** → Add an element
* **Delete** → Remove an element

### 🔧 Auxiliary Operations

* Delete entire list
* Count number of nodes
* Find nth node from end

---

## 🔹 Why Linked Lists?

Both arrays and linked lists store collections of data, but:

* Arrays are **fixed-size**
* Linked lists are **flexible**

👉 Linked lists are preferred when:

* Frequent insertions/deletions are needed
* Memory size is not known in advance

---

## 🔹 Arrays Overview

* Stored in **contiguous memory**
* Access elements using **index**
* Provides **O(1) constant time access**

📌 Address calculation:

```
Address = Base Address + (Index × Size of Element)
```

---

## 🔹 Advantages of Arrays

* Simple to use
* Fast access (O(1))
* Efficient caching due to memory locality

---

## 🔹 Disadvantages of Arrays

* Fixed size (static)
* Memory wastage possible
* Expensive insertion (requires shifting)
* Requires contiguous memory block

---

## 🔹 Dynamic Arrays

Dynamic arrays overcome fixed-size limitations:

* Resize automatically (grow/shrink)
* Usually double size when full
* Reduce size when underutilized

Examples:

* ArrayList (Java)
* Vector (C++)

---

## 🔹 Advantages of Linked Lists

* Dynamic size (no fixed limit)
* Efficient insertion and deletion
* No need for memory shifting
* No contiguous memory required

---

## 🔹 Disadvantages of Linked Lists

* No random access → **O(n)** access time
* Extra memory required for pointers
* Poor cache performance
* Traversal required for operations

📌 Example:

> To delete last node, traversal is needed to find previous node. 

---

## 🔹 Comparison: Linked List vs Array

| Feature           | Array         | Linked List    |
| ----------------- | ------------- | -------------- |
| Memory Allocation | Contiguous    | Non-contiguous |
| Size              | Fixed         | Dynamic        |
| Access Time       | O(1)          | O(n)           |
| Insertion         | Costly        | Efficient      |
| Memory Usage      | Less overhead | Extra pointer  |
| Cache Performance | Good          | Poor           |

---

## 🧠 Conclusion

Linked Lists are a powerful alternative to arrays when flexibility and dynamic memory allocation are required.

* Use **arrays** for fast access
* Use **linked lists** for dynamic operations

Understanding both helps in choosing the right data structure for a given problem.

---

## 🚀 Author

**Avinandan Bose**
🔗 GitHub: [https://github.com/AvinandanBose](https://github.com/AvinandanBose)

---



