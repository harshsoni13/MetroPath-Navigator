# 🚇 Metro Navigator - Java Graph Project

A Java-based Metro Navigation System that simulates how a metro route planner works. The application allows users to find the shortest path between metro stations, estimate travel distance, and calculate the ticket fare using graph algorithms and custom data structures.

This project was developed to strengthen my understanding of Graphs, Heaps, and shortest path algorithms while implementing a practical real-world application.

---

## ✨ Features

- 🔍 Find the shortest route between any two metro stations.
- 📍 Display the complete path from source to destination.
- 📏 Calculate the total travel distance.
- 💰 Calculate metro fare based on the selected route.
- ⚡ Fast route computation using graph algorithms.
- 🖥️ Simple console-based user interface.

---

## 🧠 Data Structures Used

### Graph
The complete metro network is represented as a weighted graph.

- **Vertices** → Metro stations
- **Edges** → Connections between stations
- **Weights** → Distance between connected stations

### Min Heap (Priority Queue)

A custom heap implementation is used to optimize shortest path calculations.

---

## ⚙️ Algorithms Implemented

### Dijkstra's Algorithm
Used to determine the shortest route between two metro stations based on edge weights.

### Breadth First Search (BFS)
Used for graph traversal and exploring station connectivity.

### Depth First Search (DFS)
Implemented to understand graph traversal and connectivity.

---

## 📂 Project Structure

```
Metro-App/
│
├── Main.java          # Application entry point
├── Graph.java         # Metro graph implementation
├── Heap.java          # Custom Min Heap
├── MetroMap.java      # Metro station and route data
├── Pair.java          # Utility class
└── README.md
```

---

## 🚀 How It Works

1. Start the application.
2. Enter the source station.
3. Enter the destination station.
4. The application computes:
   - Shortest route
   - Total distance
   - Estimated fare
5. The complete route is displayed.

---

## 💰 Fare Calculation

The fare is calculated programmatically using the total distance of the selected route.

The calculation logic is modular, making it easy to modify fare rules or pricing slabs according to different metro systems.

---

## 💻 Technologies Used

- Java
- Object-Oriented Programming
- Graph Data Structure
- Heap Data Structure
- Dijkstra Algorithm
- BFS
- DFS

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Graph representation using Java
- Weighted graph traversal
- Shortest path algorithms
- Heap implementation from scratch
- Object-Oriented Design
- Time complexity optimization
- Java Collections Framework

---

## ▶️ Running the Project

### Requirements

- Java 8 or above
- Any Java IDE
  - IntelliJ IDEA
  - Eclipse
  - VS Code
  - NetBeans

### Steps

```bash
git clone https://github.com/yourusername/Metro-App.git

cd Metro-App

javac *.java

java Main
```

---

## 📸 Sample Output

```
Enter Source Station:
Rajiv Chowk

Enter Destination Station:
Noida City Centre

Shortest Route:
Rajiv Chowk
↓
Barakhamba Road
↓
Mandi House
↓
Akshardham
↓
Noida City Centre

Total Distance : 18 km

Estimated Fare : ₹40
```

---

## 🔮 Future Improvements

- GUI using Java Swing / JavaFX
- Real-time metro map visualization
- Interchange station highlighting
- Multiple metro line support
- Travel time estimation
- Station search and auto-suggestions
- Save recent routes
- Export route details

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Author

**Harsh**

If you found this project useful, consider giving it a ⭐ on GitHub!
