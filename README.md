# React 18 New Features Repository

This repository is dedicated to the implementation of new features introduced in React 18. Each feature is implemented in a separate file within the project.

## Project Hierarchy

.
├── createRootFeature.js
├── batchingFeature.js
├── concurrentFeature.js
├── ...
└── README.md


## Features

### 1. New Render API (Root)
- File: `createRootFeature.js`
- Description: This file contains the implementation of the new Render API with `createRoot` and `hydrateRoot` functions.

### 2. Batching
- File: `batchingFeature.js`
- Description: This file implements the batching feature in React 18.

### 3. Concurrent Mode
- File: `concurrentFeature.js`
- Description: Here you'll find the implementation of Concurrent Mode, including `useTransition` and `useDeferredValue`.

## Usage

To use any of these features in your React application, you can simply import the corresponding file.

```javascript
import { createRoot, hydrateRoot } from './createRootFeature';
import { startBatching } from './batchingFeature';
import { useTransition, useDeferredValue } from './concurrentFeature';
