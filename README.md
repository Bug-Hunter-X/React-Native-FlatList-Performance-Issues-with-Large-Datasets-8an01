# React Native FlatList Performance Issue

This repository demonstrates a common performance issue encountered when using `FlatList` in React Native with large datasets and complex item rendering.  The issue leads to crashes or freezes, especially on lower-end devices.  The solution provided employs techniques like `windowSize`, `getItemLayout`, and optimization of item rendering to mitigate this problem. 

## Reproducing the Issue

1. Clone the repository.
2. Run `npm install`.
3. Run the app on a device or emulator.  Notice performance degradation or crashes when scrolling through the list.

## Solution

The solution focuses on optimizing the rendering process of the `FlatList` to improve performance. The changes include setting `windowSize`, implementing `getItemLayout`, and optimizing item component rendering to reduce overhead. See `FlatListBugSolution.js` for details.

## Technologies Used

* React Native
* JavaScript