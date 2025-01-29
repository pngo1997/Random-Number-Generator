# 🏗️ War and Random Numbers
## 📜 Overview
This project explores pseudo-random number generation (PRNG) using the text of War and Peace as a source of randomness. It evaluates different PRNG techniques and compares them against standard Python libraries. The objective is to analyze how random number generation behaves when derived from natural text data and whether it can be used as an effective random number source.

## 🎯 Problem Explanation
In many applications, random numbers are critical, such as in cryptography, simulations, and statistical sampling. Traditional PRNGs rely on mathematical functions, but this project investigates whether a novel PRNG approach using the text of War and Peace can provide a viable alternative.

1. War and Peace PRNG:
- Extracts numerical values from the text.
- Uses them to generate sequences of random numbers.
- Compares its performance against traditional PRNG methods.
2. Evaluation Metrics:
- Distribution Analysis – Are the generated numbers uniformly distributed?
- Statistical Tests – Do the generated numbers pass randomness tests?
- Performance Comparisons – How does the custom PRNG compare with Python’s random module?

## 🛠️ Implementation Details
1. Extracting Randomness:
- The text of War and Peace is processed, and numeric transformations are applied to extract randomness.
- The project uses seeded PRNGs with different step sizes and starting positions to observe variations.
2. Testing and Validation:
- Multiple test cases are run to compare the output of the War and Peace PRNG against traditional PRNGs.
- Key statistical measures (such as mean, standard deviation, and randomness tests) are computed to evaluate performance.
