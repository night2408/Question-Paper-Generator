# Question-Paper-Generator
This project is a C++ application that generates a question paper for a university exam. It randomly selects questions from three different difficulty levels: Easy, Medium, and Hard, and then organizes them into sections with respective marks.

## Introduction

The Question Paper Generator is designed to automatically create a question paper with a predefined structure and total marks. It uses random selection to choose questions from different difficulty levels, ensuring that each generated paper is unique. The program keeps track of previously selected questions to avoid repetition.

## Features

- Randomly generates questions for a university exam paper.
- Questions are categorized into three difficulty levels: Easy, Medium, and Hard.
- Ensures previously used questions are not repeated in subsequent runs.
- Allows customization of the number of questions for each difficulty level.
- Calculates total marks and compares it with the predefined total to avoid exceeding the limit.

## Requirements

- C++ Compiler (GCC, Clang, etc.)
- C++ Standard Library
- Input text files containing questions (EASY.txt, MEDIUM.txt, HARD.txt)

