# DTW with Confidence Interval
Author: Huaze (Patrick) Liu, Hamza Jamal, Jeremy Kim, Javier Perez

Date: May 2024

Upload Date: June 2024

This is the final project for ENGR207 HM -- Digital Signal Processing

## Overview
This repository contains the implementation and analysis of Dynamic Time Warping (DTW) with Confidence Intervals, where we explored methodologies to measure the reliability of alignment intervals within the DTW framework. The project introduces novel metrics and visualizations for evaluating the alignment confidence across the DTW path, focusing on specific areas where two signals match or diverge.

## Features
 - Dynamic Time Warping (DTW): Utilizes dynamic programming to align two segments of time series data with varying speeds.
 - Confidence Intervals: Implements techniques to measure the confidence of alignments at specific points along the DTW path.
 - Valley Width Analysis: Introduces the concept of "Valley Width" in the cost matrix to evaluate alignment sensitivity.
 - Sliding Window Comparison: Compares segments of the DTW path using FlexDTW to assess alignment accuracy.
 - Dynamic Programming: Utilized to compute the pairwise cost matrix and find the optimal alignment path in DTW.
