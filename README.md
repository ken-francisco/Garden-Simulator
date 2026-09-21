# 🌾 Garden Plot: A DSA Garden Simulator

An interactive, web-based application demonstrating the practical application of four core **Data Structures and Algorithms (DSA)** concepts through managing a $16 \times 16$ garden plot.

---

## 🚀 Key Features & DSA Implementation

### 1. 🧱 2D Matrix Array (`GardenGrid`)
* **Usage:** Represents the $16 \times 16$ garden plot (256 individual soil cells).
* **Efficiency:** Provides $O(1)$ time complexity for accessing and updating the state of any given plot (`cells[r][c]`).

### 2. 🥞 LIFO Action Stack (`ActionStack`)
* **Usage:** Manages the entire action history to power the **Undo** and **Redo** functionalities.
* **Dual-Stack Pattern:** Employs two separate stacks (`actions` and `redoStack`) for precise state reversal and re-application of moves.

### 3. 🚶‍♂️ FIFO Task Queue (`TaskQueue`)
* **Usage:** Schedules watering operations in the exact order they were added to the queue.
* **Optimization:** Utilizes an explicit `#head` pointer to achieve $O(1)$ amortized `dequeue()` operations instead of costly $O(N)$ `shift()` operations.

### 4. 🌲 Hierarchical N-Ary Tree (`TreeNode`)
* **Usage:** Organizes the plant classification taxonomy (`Botanical Garden` $\rightarrow$ `Flora/Crops` $\rightarrow$ `Flowers/Vegetables` $\rightarrow$ `Species`).
* **Visual Traversals:** Demonstrates animated tree walks using **DFS** (via Stack) and **BFS** (via Queue), along with post-order recursive subtotal calculations.

---

## 🛠️ Tech Stack

* **Language:** Vanilla JavaScript (ES6+ Classes & Private Fields `#`)
* **Structure & Styling:** HTML5, Modern CSS Grid & Custom Properties (CSS Variables)
* **Storage:** Browser `localStorage` API for state persistence
* **Zero Dependencies:** Built entirely without external libraries or frameworks

---
