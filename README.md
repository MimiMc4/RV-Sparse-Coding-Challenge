# RV-Sparse: Coding Challenge

This repository contains a solution to the RV-Sparse coding challenge.

## Challenge
Implement the sparse_multiply function that:

- Scans a row-major matrix A and identifies its non-zero elements.
- Extracts them into Compressed Sparse Row (CSR) format using caller-provided buffers.
- Computes the matrix-vector product y = A * x using the extracted CSR data.
- Writes the result directly into a caller-provided output buffer.

Critical Constraint: Your function must perform zero dynamic memory allocation. All memory is pre-allocated by the caller.
