# Barbershop Scheduling Optimization

Welcome to the <span style="font-size:24px; color:blue;">Barbershop Scheduling Optimization</span> project repository! This project aims to maximize profits for a barbershop by efficiently scheduling appointments while considering various constraints. The provided code implements a <strong>Genetic Algorithm</strong> approach to achieve this optimization.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Problem Statement](#problem-statement)
- [Genetic Algorithm](#genetic-algorithm)
- [Model Variations](#model-variations)
- [Results and Analysis](#results-and-analysis)
- [Conclusion](#conclusion)

## Introduction

In a barbershop, scheduling appointments can be a complex task. This project tackles the challenge of scheduling appointments for multiple barbers while considering factors such as customer types, operation costs, time requirements, and potential discounts for customers.

## Setup

Clone this repository to your local machine and make sure you have the required dependencies installed. The primary libraries used in this project are <span style="color:green;">NumPy</span>, <span style="color:green;">random</span>, and <span style="color:green;">Matplotlib</span>. These libraries are essential for data manipulation, random number generation, and result visualization.

## Problem Statement

The goal of this project is to optimize the scheduling of appointments in a barbershop to maximize profits. This involves assigning customers to different barbers, considering the type of service they require, and balancing various factors like operation costs, customer types, and potential discounts.

## Genetic Algorithm

The core approach of this project is the use of a <strong>Genetic Algorithm (GA)</strong> to find the best scheduling arrangement. The GA evolves a population of potential solutions (schedules) over multiple generations. Parents are selected from the population based on their fitness (profit), and offspring are generated through crossover and mutation operations. The offspring are then evaluated and added to the population if they meet certain criteria.

## Model Variations

The project explores two variations of the optimization model:

1. **Model 1**: The initial model considers customer types, operation costs, time requirements, and membership discounts. It employs a <strong>Genetic Algorithm</strong> to evolve schedules over multiple generations, aiming to maximize the barbershop's profits.

2. **Model 2**: The enhanced model includes an additional parameter - membership fees. It investigates how different membership fee levels impact the barbershop's profits. The <strong>Genetic Algorithm</strong> is applied to find the optimal membership fee that maximizes profits.

## Results and Analysis

The project provides valuable insights into how different customer types, operation costs, time requirements, discounts, and membership fees impact the overall profits of the barbershop. The included graphs visualize the optimization process, showing the evolution of profits over generations and the impact of varying membership fees.

## Conclusion

Optimizing barbershop scheduling is a complex task that involves balancing various factors to maximize profits. This project demonstrates the use of <strong>Genetic Algorithms</strong> to find efficient scheduling solutions. By exploring different model variations and analyzing results, the project sheds light on how various parameters influence the barbershop's profits.

Feel free to explore the code and adapt it to your own scheduling optimization challenges. If you have any questions or suggestions, don't hesitate to open an issue or reach out to the project maintainers.

Thank you for visiting the <span style="color:blue;">Barbershop Scheduling Optimization</span> repository!
