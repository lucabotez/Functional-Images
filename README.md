Copyright @lucabotez

# Functional Images

## Overview
**Functional Images** is a Haskell project that explores **functional programming techniques** for **image generation and manipulation** using mathematical representations of regions and transformations. The project builds upon **shallow and deep embeddings** to create and transform images using algebraic structures.

## Features
- **Mathematical Representation of Images** using functions and regions.
- **Transformations and Compositions** (Translation, Scaling, and Combinations).
- **Boolean Operations on Regions** (Union, Intersection, Complement).
- **Deep and Shallow Embeddings** of transformations and image structures.
- **Optimizations and Simplifications** using algebraic properties.

## Project Structure
- **`Shallow.hs`** – Implements **shallow embeddings**, treating regions as characteristic functions.
- **`Deep.hs`** – Implements **deep embeddings** using abstract syntax trees (ASTs) for transformations.
- **`Folds.hs`** – Introduces **higher-order functions** (folds) for recursive processing and structure optimization.

## Implementation Details
### **1. Shallow Embedding (`Shallow.hs`)**
- Defines **Regions** as functions `(Point -> Bool)`.
- Implements **basic shapes**: `circle`, `rectangle`, and **point-based regions**.
- Supports **Boolean operations**: `union`, `intersection`, and `complement`.
- Implements **geometric transformations**: `translation`, `scaling`, and **function application**.

### **2. Deep Embedding (`Deep.hs`)**
- Represents transformations and regions as **abstract syntax trees (ASTs)**.
- Allows interpretation of transformations and regions in multiple ways.
- Provides **AST optimizations**, such as **simplifying transformations** and **merging consecutive operations**.

### **3. Functional Folding (`Folds.hs`)**
- Introduces **higher-order functional operations** on region and transformation structures.
- Implements **folds** for recursive data processing.
- Provides a generic **region transformation system**.
- Optimizes transformation sequences through **composition and simplification**.

## Notes
- **Lazy evaluation** enables efficient computation of **infinite image structures**.
- **Higher-order functions** allow flexible manipulation of images and transformations.
- The project demonstrates **both shallow and deep embeddings** of image representation.
