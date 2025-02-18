# Mutable vs. Immutable References in Rust

This repository demonstrates a common error in Rust programming related to mutable and immutable references. The example shows how attempting to modify a value through an immutable reference leads to a compile-time error.

## Bug Description
The `bug.rs` file contains code that creates a mutable reference (`y`) and an immutable reference (`z`) to the same variable. While modifying the value through the mutable reference is permitted, attempting to modify it through the immutable reference results in a compilation error. This showcases the strict rules Rust enforces regarding borrowing and mutability.

## Solution
The `bugSolution.rs` file provides a corrected version of the code. The solution emphasizes the importance of understanding and correctly using mutable and immutable references to avoid common pitfalls in Rust programming.