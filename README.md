# Lab-report-03
Title : Graph Coloring 

Name: Mahinul Islam Rabby
Id: 232002011
Section:232_D7
Course code : CSE316 

## OBJECTIVES/AIM 

The objective of this experiment are:   
1. To implement the graph coloring problem in Python
2. To determine the graph coloring algorithm using the backtracking technique 
3. To check whether a graph can be colored using a limited number of colors (K colors).

## How to Run
Lab report 3.py

You are given an undirected graph with N vertices and M edges. Your task is to implement a Python program that uses Backtracking to determine whether the graph can be colored using K colors such that no two adjacent vertices share the same color. The input will be read from a file, where the first line contains three integers: N (number of vertices, numbered from 0 to N−1), M (number of edges), and K (number of available colors). Each of the following M lines contains two integers u and v, representing an undirected edge between vertex u and vertex v.

Case#1Input:
4 5 3
0 1
0 2
1 2
1 3
2 3

Case#1Output:
Coloring Possible with 3 Colors
Color Assignment: [1, 2, 3, 1]

Case#2Input:
4 5 2
0 1
0 2
1 2
1 3
2 3

Case#2Output:
Coloring Not Possible with 2 Colors
