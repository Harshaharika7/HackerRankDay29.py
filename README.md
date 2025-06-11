## 📘 Day 29: Bitwise AND | HackerRank 30 Days of Code

This repository contains the Python solution for Day 29 of the HackerRank 30 Days of Code challenge, focusing on bitwise operations and optimal logic under constraints.

## 🚀 Challenge Summary

-You're given two integers, N and K. From the set {1, 2, ..., N}, find the maximum value of 
A & B such that:

    -A < B
    
    -A & B < K

-Return this maximum possible value of A & B that is still less than K.

## 📝 Problem Statement

Given multiple test cases with values of N and K, compute the required maximum.

## ✅ Constraints

        -1 ≤ T ≤ 1000
        
        -2 ≤ N ≤ 10⁶
        
        -0 < K < N

## 🔢 Sample Input

          3
          5 2
          8 5
          2 2

## ✅ Sample Output

          1
          4
          0

## 💡 Explanation

          -For (5, 2): maximum (A & B) < 2 is 1
          
          -For (8, 5): maximum (A & B) < 5 is 4
          
          -For (2, 2): only possible is (1, 2) → 0
          
          -Used efficient bit manipulation logic to avoid brute force for large N.

## 🧠 Concepts Practiced

-Bitwise AND operation

-Optimization under constraints

-Mathematical deduction

-Loop minimization with binary rules

## 🛠 How to Run

Option 1: With input file
    
        python3 bitwise_and.py < input.txt

Option 2: Manual input

        python3 bitwise_and.py

## 🔗 HackerRank Challenge Link

        HackerRank – Day 29: Bitwise AND

🏆 Challenge Completed

✅ Problem Solved

🎯 Points Earned: 30

## 📅 Completed On

        10th June 2025

## 🔖 Tags

#Python #HackerRank #Bitwise #30DaysOfCode #Day29Challenge #ProblemSolving #EfficientLogic #Optimization #BinaryOperators

## ✍ Author

        Harsha M
        
        GitHub: @Harshaharika7
        
        LinkedIn: Harsha M
