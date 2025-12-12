# testMouseHover

Mouse Hover Performance Test Tool for measuring hover response times in remote desktop environments.

## Overview

This tool helps measure and compare the performance of mouse hover interactions in Citrix/RDP sessions. It's designed to test and validate improvements to hover highlight lag issues in Windows Server 2019 environments.

## Features

- Real-time hover response time measurement
- Interactive UI elements (buttons and menu items)
- Detailed performance metrics:
  - Average, Min, Max response times
  - Standard deviation
  - Events per second
  - Test duration tracking
- Visual response time chart
- Export results as JSON for comparison

## Usage

1. Open `hover-performance-comparison.html` in a browser on your target environment
2. Enter a descriptive session label (e.g., "Original Implementation" or "Enhanced Implementation")
3. Click "Start Test"
4. Move your mouse over the buttons and menu items
5. Click "Export Results" to save the performance data
6. Repeat on different connections/implementations to compare

## Live Demo

Visit the [GitHub Pages site](#) to try it online.

## Purpose

This tool was created to validate improvements to mouse hover performance in Citrix live desktop sessions, specifically addressing the issue where hover highlights lag behind actual pointer movement.
