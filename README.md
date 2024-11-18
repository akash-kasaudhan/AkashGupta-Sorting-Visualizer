# AkashGupta-Sorting-Visualizer
 Sorting Visualizer Sorting algorithms are fundamental to computer science and play a vital role in organizing data efficiently. This project is a Sorting Visualizer that demonstrates the working of some of the most popular sorting algorithms. By visualizing the sorting process,
# Sorting Visualizer  

Visualization of different sorting algorithms using **C++** and the **SDL2 Library**.  

---

## 📜 Project Description  
Sorting algorithms are crucial for organizing data efficiently. This project, **Sorting Visualizer**, allows users to visually comprehend the operations of different sorting algorithms.  

### Supported Sorting Algorithms  
- **Selection Sort**  
- **Insertion Sort**  
- **Bubble Sort**  
- **Merge Sort**  
- **Quick Sort**  
- **Heap Sort**  

### Features  
1. **Fixed List Size**: The visualizer operates on a fixed list of **130 elements**.  
2. **Randomized Input**: Generate random lists to observe how algorithms handle different data arrangements.  
3. **Custom Algorithm Selection**: Choose any algorithm to sort the list in **ascending order**.  
4. **Controlled Visualization**:  
   - Faster algorithms like **Merge Sort** and **Quick Sort** are intentionally slowed for better visualization.  
   - Simulates the logical steps of each algorithm to enhance understanding.  

---

## 🚀 How to Run  

### **Option 1: Using Prebuilt Release**  
1. Download the release package.  
2. Run the application file: `Sorting Visualizer.exe`.  

### **Option 2: Using C++ Source Code**  
1. Clone or download the repository.  
2. Ensure you have the **SDL2 library** installed and configured. Follow [Lazy Foo's SDL2 Tutorial](https://lazyfoo.net/tutorials/SDL/) for setup instructions.  
   - **Note**: Use the `x86_64-w64-mingw32` folder instead of `i686-w64-mingw32` to configure the **64-bit** SDL2 library.  
3. Include the `Sorting Visualizer.cpp` file in your project.  
4. Use the build options provided in the tutorial, then build and run the project.  

---

## 🎮 Controls  

**⚠️ Note**: Avoid giving repetitive commands before the execution of the current command is completed. This may cause unexpected behavior.  

| Key | Action |  
|-----|--------|  
| `0` | Generate a new randomized list |  
| `1` | Start **Selection Sort** |  
| `2` | Start **Insertion Sort** |  
| `3` | Start **Bubble Sort** |  
| `4` | Start **Merge Sort** |  
| `5` | Start **Quick Sort** |  
| `6` | Start **Heap Sort** |  
| `q` | Exit Sorting Visualizer |  

---

## 🛠️ Technical Notes  
- **Language**: C++  
- **Library**: SDL2  
- **Platform**: Windows (64-bit)  

The sorting time visualized does not reflect the exact theoretical time complexity of the algorithms. Faster algorithms like **Merge Sort** and **Quick Sort** are delayed for proper visualization.  

---

## 🧩 Future Enhancements  
- Add support for additional sorting algorithms.  
- Enable customization of list size and visualization speed.  
- Provide detailed statistics and performance metrics for each sorting algorithm.  

---



