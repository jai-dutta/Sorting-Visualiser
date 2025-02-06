# Sorting Algorithm Visualizer

A Python-based visualization tool that demonstrates various sorting algorithms in real-time using Pygame. Watch how different sorting algorithms manipulate arrays with a dynamic, color-coded display.

## Features

- Real-time visualization of sorting algorithms
- Multiple sorting algorithms implemented:
  - Bubble Sort
  - Insertion Sort
  - Selection Sort
  - Merge Sort
  - Quick Sort
- Adjustable visualization parameters:
  - Array size (50, 125, 200, 250, 500 elements)
  - Animation delay speed
- Color-coded visualization:
  - White: Unsorted elements
  - Red: Current comparison element
  - Green: Selection sort swap position
  - Blue: Pivot element (Quick Sort)

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Ensure Python 3.x is installed on your system
2. Install Pygame using pip:
```bash
pip install pygame
```
3. Download the source code and run the script:
```bash
python sorting_visualizer.py
```

## Controls

- `[g]` - Generate new random array
- `[b]` - Run Bubble Sort
- `[i]` - Run Insertion Sort
- `[s]` - Run Selection Sort
- `[m]` - Run Merge Sort
- `[q]` - Run Quick Sort
- `[↑]` `[↓]` - Adjust animation delay
- `[←]` `[→]` - Change array size
- Close window to exit

## How It Works

The visualizer creates a window displaying vertical bars representing array elements, where the height of each bar corresponds to the value it represents. As the sorting algorithms run, the visualization updates in real-time to show how elements are being compared and swapped.

Different colors are used to highlight important elements during the sorting process:
- The red bar indicates the current element being compared
- The green bar (in Selection Sort) shows the current minimum element position
- The blue bar indicates the pivot element in Quick Sort

## Performance Notes

- The visualization speed can be adjusted using the up/down arrow keys
- Larger array sizes will naturally take longer to sort
- Different sorting algorithms have different time complexities:
  - Bubble Sort: O(n²)
  - Insertion Sort: O(n²)
  - Selection Sort: O(n²)
  - Merge Sort: O(n log n)
  - Quick Sort: O(n log n)

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features. Some possible enhancements could include:
- Additional sorting algorithms
- More visualization options
- Performance optimizations
- Additional array size options
