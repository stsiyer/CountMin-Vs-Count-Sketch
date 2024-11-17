# CountMin-Vs-Count-Sketch

This repository contains a **Jupyter Notebook** to compare two popular probabilistic data structures: **CountMin Sketch** and **Count Sketch**. Both algorithms are used for approximate frequency counting in data streams, offering memory-efficient solutions for large-scale data processing. The notebook provides a detailed comparison of both methods by analyzing their performance in terms of **Mean Absolute Error (MAE)** and **Mean Relative Error (MRE)**.

### Key Features:
- **CountMin Sketch**: A probabilistic data structure that estimates the frequency of elements in a stream while minimizing memory usage.
- **Count Sketch**: Similar to CountMin, but with random sign functions to improve accuracy by considering both the magnitude and direction of hash values.

### Configuration Details:
- **Stream Length**: \(10^6\)
- **Number of Distinct Elements**: \(10^5\)
- **Epsilon**: 0.1
- **Delta**: 0.1
- **Matrix Size**: 4000

### Usage:
1. Clone or download this repository.
2. Open the Jupyter Notebook (`Count Vs CountMin Sketch.ipynb`).
3. Run the notebook cells to explore the implementation, modify parameters like stream length, distinct elements, epsilon, and delta, and observe the resulting performance comparisons.
