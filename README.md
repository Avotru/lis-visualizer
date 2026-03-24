# LIS Visualizer Ultra

An interactive single-file visualizer for the **Longest Increasing Subsequence (LIS)** problem, built using **HTML, CSS, JavaScript, and SVG**.

## Overview

This project demonstrates how the Longest Increasing Subsequence problem can be solved and visualized using two approaches:

- **Dynamic Programming — O(n²)**
- **Binary Search / Patience Sorting — O(n log n)**

The tool is designed to be educational and interactive, with animated steps, synchronized pseudocode, clickable history, and complexity analysis.

## Features

- Single-file implementation
- No external libraries or dependencies
- Dark responsive UI
- Custom input array
- Preset test cases
- Step-by-step playback controls
- Animated visualization
- Pseudocode highlighting with tooltips
- Action history and timeline jumping
- Reconstructed LIS display
- Complexity analysis section
- Search role and impact explanation
- Works on GitHub Pages and other static hosts

## Algorithms Included

### 1. Dynamic Programming
The DP method computes the LIS length by checking all previous positions for every index.

**Time Complexity:** O(n²)  
**Space Complexity:** O(n)

### 2. Binary Search / Patience Sorting
The optimized method uses a tails array and binary search to reduce the time complexity.

**Time Complexity:** O(n log n)  
**Space Complexity:** O(n)

## Educational Goals

This project supports the following learning outcomes:

- Understand LIS problem-solving strategies
- Visualize Dynamic Programming state updates
- Understand the role of binary search in optimization
- Compare algorithm growth and efficiency
- See the effect of correct vs incorrect search rules

## How to Use

1. Open the page
2. Enter a custom input array or choose a preset
3. Select the algorithm:
   - Dynamic Programming
   - Binary Search / Patience
4. Click **Build Steps**
5. Use:
   - **Step**
   - **Play**
   - **Pause**
   - **Reset**
6. Explore:
   - pseudocode tracker
   - timeline
   - action history
   - complexity analysis
   - impact explanation

## Example Test Cases

- `10,9,2,5,3,7,101,18` → LIS length = `4`
- `0,1,0,3,2,3` → LIS length = `4`
- `7,7,7,7` → LIS length = `1`
- `5,4,3,2,1` → LIS length = `1`

## File Structure

This project is intentionally simple:

- `index.html` → complete project in one file

## Deployment

This project is a static website and can be deployed easily on:

- GitHub Pages
- Netlify
- Vercel
- Any normal static host

## Author

**Zuhair Halawa**

## Copyright

LIS Visualizer Project — Zuhair Halawa © 2026
