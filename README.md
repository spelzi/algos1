# Orthogonal Vectors Determination Algorithm

This repository contains an algorithm to determine whether pairs of given vectors are orthogonal using dot product calculations.

## Problem Statement

Given a number of pairs of vectors in IR (real numbers), the algorithm calculates the dot product of each pair of vectors and determines whether they are orthogonal. The dot product of two orthogonal vectors is zero.

## Algorithm Overview

The algorithm consists of two main parts: the `dot_product` procedure and the `determine_orthogonal_vectors` algorithm. It utilizes arrays for representing vectors, nested loops for vector processing, and different types of parameter passing.

### `dot_product` Procedure

- Input: Two arrays `vector1` and `vector2` representing vectors, and the number of elements `n` in the vectors.
- Output: None (updates `dot_product_sum`)

The procedure calculates the dot product of two vectors by iterating through their elements using a nested loop. The dot product sum is initialized and updated as the loop progresses.

### `determine_orthogonal_vectors` Algorithm

- Input: Number of pairs `n`, arrays `vector1` and `vector2` representing vectors.
- Output: An array `orthogonal` of Boolean values indicating orthogonality.

The algorithm determines the orthogonality of each pair of vectors by calling the `dot_product` procedure. It calculates the dot product result for each pair and checks if the result is zero. If it is, the vectors are orthogonal, and the corresponding element in the `orthogonal` array is set to `True`.

## Usage

1. Provide the input pairs of vectors and the number of elements in each vector.
2. Run the algorithm.
3. The `determine_orthogonal_vectors` algorithm will return an array of Boolean values indicating the orthogonality of each pair.

## Example

```python
# Example input
n = 2
vector1 = [[3, 1, 7, 9], [1, 2, 3, 4]]
vector2 = [[2, 4, 1, 9], [4, 3, 2, 1]]

# Run the algorithm
orthogonal = determine_orthogonal_vectors(n, vector1, vector2)

# Print the result
print("Orthogonality results:", orthogonal)

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/st_manuel" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="st_manuel" height="30" width="40" /></a>
<a href="https://linkedin.com/in/emmanuel-chidiebube-uzor" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="emmanuel-chidiebube-uzor" height="30" width="40" /></a>
<a href="https://instagram.com/st_manuel" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="st_manuel" height="30" width="40" /></a>
</p>