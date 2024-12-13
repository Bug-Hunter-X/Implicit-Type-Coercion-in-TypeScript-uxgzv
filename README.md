# Implicit Type Coercion in TypeScript

This repository demonstrates a common issue in TypeScript where implicit type coercion can lead to unexpected behavior and bypasses type safety.  The example uses functions with different parameter types, highlighting how using the `any` type weakens type checking.

## Problem

TypeScript's `any` type allows any kind of value.  While convenient for flexibility, it disables compile-time type checking, making it harder to find errors.

## Solution

The best way to avoid this is to avoid using `any` unless absolutely necessary.  Be explicit with types and handle different data types appropriately.  Consider using type guards or conditional logic for more complex scenarios.