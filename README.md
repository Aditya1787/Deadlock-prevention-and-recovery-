# Deadlock-prevention-and-recovery-

# Deadlock Toolkit 🛠️

A visual simulator for understanding deadlocks in operating systems, featuring interactive resource allocation graphs and deadlock detection algorithms.

![Deadlock Toolkit Screenshot](screenshot.png) *(add a screenshot later)*

## Features ✨

- **Interactive Resource Allocation Graph (RAG) Visualization**
  - Processes (circles) and Resources (rectangles)
  - Allocation edges (solid lines)
  - Request edges (dashed lines)
  - Deadlock cycles highlighted in red

- **Complete Deadlock Operations**
  - Banker's Algorithm for safe state detection
  - Cycle detection for deadlock identification
  - Process termination for deadlock recovery

- **Intuitive Controls**
  - Configure processes and resources
  - Set maximum demands
  - Create allocations and requests
  - Run safety checks and deadlock detection

## Technologies Used 💻

- **Frontend**: HTML5, CSS3, JavaScript
- **Visualization**: [D3.js](https://d3js.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Hosting**: GitHub Pages

## How to Use 🚀

1. **Initialize**:
   - Set number of processes (1-6) and resources (1-4)
   - Click "Initialize" button

2. **Set Demands**:
   - Format: `P1:R1=3,R2=2` (Process 1 needs 3 of R1 and 2 of R2)
   - Click "Set Demand"

3. **Create Allocations/Requests**:
   - Allocation format: `P1->R1:1` (Process 1 gets 1 unit of R1)
   - Request format: `P1->R1:1` (Process 1 requests 1 unit of R1)
   - Use respective buttons

4. **Analyze**:
   - Run Banker's Algorithm for safety check
   - Check for deadlocks
   - Recover from deadlocks if detected

## Live Demo 🌐

The project is hosted on GitHub Pages:  
[View Live Demo](https://aditya1787.github.io/Deadlock-prevention-and-recovery-/)

## Installation 📦

To run locally:
```bash
git clone https://github.com/your-username/deadlock-toolkit.git
cd deadlock-toolkit
# Open index.html in your browser
