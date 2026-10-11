# Segment Intersection

A JavaScript project that calculates and visualises the intersection point of two line segments using linear interpolation (lerp).

## Overview

This project uses HTML Canvas to display two line segments and calculate their intersection point in real time. One segment moves around the mouse cursor, while the other stays fixed.

The intersection point is displayed whenever the two segments cross within their endpoints. If they do not intersect, no intersection point is shown.

## Features

- Visualises two line segments using HTML Canvas.
- Calculates the intersection point using linear interpolation.
- Checks whether the intersection lies within both segments.
- Returns `null` when no single intersection point exists.
- Updates the visualisation in real time as the segments move.

## Technologies Used

- HTML
- CSS
- JavaScript
- HTML Canvas API

## How to Run

1. Clone or download this repository.
2. Open the `index.html` file in a web browser.
3. Move the mouse around to see how the line segments intersect.

## How It Works

The intersection is calculated by representing each line segment parametrically and solving for the parameters where their coordinates match.

The resulting parameters are checked to make sure the intersection lies within both line segments, rather than only on the infinite lines containing them.
