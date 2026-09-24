​🌿 Dynamic Garden Simulator: DSA Game Engine

​An advanced, interactive, web-based gamified farming simulator built to demonstrate the practical implementation of core Data Structures and Algorithms (DSA) principles through real-time grid simulation, embedded Python scripting, and modular system design.

​🚀 Key Features & DSA Implementation
​1. 🧱 2D Matrix Array (gardenGridState)
​Usage: Manages the scalable 5\times5 dynamic garden plot grid, keeping track of plot coordinates, planting states, hydration levels, and growth ticks.
​Efficiency: Provides O(1) direct access and lookup complexity for modifying individual soil cell properties via matrix indices (grid[row][col]).

​2. 🥞 LIFO Action Stack (actionLogs)
​Usage: Operates on a Last-In, First-Out (LIFO) protocol to maintain a real-time audit trail and history of user operations (such as seed purchases, tool applications, and planting actions).
​Efficiency: Delivers O(1) push and pop execution speeds for dynamic event logging and tracking.

​3. 🚶‍♂️ FIFO Task Queue (TaskQueue & Auto-Farm Bot)
​Usage: Coordinates sequential game processes, climate event handlers, and automated tasks—such as the Auto-Farm Bot scanning and irrigating dry plots.
​Efficiency: Implements First-In, First-Out (FIFO) mechanics to process automated farming routines seamlessly without blocking the main UI thread.

​4. 🌲 Hierarchical N-Ary Tree (PlantClassification)
​Usage: Structures plant taxonomy from the root registry down to expanded rarity categories and species (Flowers, Succulents, Crops & Fruits, and Cosmic & Divine tiers).
​Visual Traversals: Demonstrates taxonomic relationships and tree traversal capabilities across all added tiers from Common up to Prismatic and Divine (Crystal Rose, Rainbow Tree, Yggdrasil Seedling, etc.).

​5. 🐍 Embedded Python Runtime (Pyodide)
​Usage: Bridges frontend DOM events with a WebAssembly Python 3 runtime, allowing students to run backend DSA scripts directly inside the browser console.

​🛠️ Technical Stack & Environment
​Frontend Architecture: HTML5, Tailwind CSS, Vanilla JavaScript (ES6+), and Lucide Icons.
​Python Runtime: Pyodide (WebAssembly integration for browser-based Python script execution).
​State Management & Mechanics: Custom helper functions, hash lookups for crop mutations, rarity valuation multipliers, and dynamic seed rolling filters.
