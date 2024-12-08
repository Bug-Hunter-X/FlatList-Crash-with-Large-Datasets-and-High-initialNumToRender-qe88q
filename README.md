# React Native FlatList Performance Issue

This repository demonstrates a common performance issue in React Native's FlatList component when dealing with large datasets and an improperly configured `initialNumToRender` prop.  The issue leads to crashes or unresponsiveness due to excessive memory usage.

## Bug Reproduction

The `bug.js` file contains code that reproduces the issue.  You'll need to run this code with a large dataset to observe the performance degradation or crash.

## Solution

The `bugSolution.js` file provides a solution. It demonstrates how to optimize the FlatList component by reducing the `initialNumToRender` prop to a more manageable value and potentially using other optimization techniques like windowSize.