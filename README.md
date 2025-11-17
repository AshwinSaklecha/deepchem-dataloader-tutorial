# DeepChem DataLoader Tutorial

## Why I Made This

I was going through DeepChem tutorials and checked out the tutorial wishlist. Noticed there wasn't anything on DataLoaders. Since I'd already done the Dataset tutorial, I thought this would be a good next step to work on.

## How I Built It

Pretty straightforward process:

- Went through the relevant code files in the DeepChem repo to understand how DataLoaders work
- Ran a bunch of code snippets to test different features
- Wrote down my thought process and notes in a Google Doc
- Put together a tutorial that starts simple and builds up to real examples

My main goal was to make it easy to understand and give people quick hands-on practice. I wanted beginners to be able to load their own datasets without getting lost.

## What's Covered

The tutorial walks through:

- What DataLoaders are and why you need them
- Using CSVLoader with custom molecular datasets
- How featurization works (using CircularFingerprint)
- Setting up multi-task learning
- Loading real datasets like Delaney solubility
- Memory management with sharding for large datasets
- Other loader types like SDFLoader
- How this compares to using MoleculeNet functions