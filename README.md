# TypeScript Type Mismatch Bug

This repository demonstrates a common type mismatch bug in TypeScript and its solution.

The `bug.ts` file contains the buggy code that attempts to pass an array to a function expecting a string. The `bugSolution.ts` file provides a corrected version that handles the type mismatch appropriately. 

## Bug Description

A type mismatch occurs when a function expects a specific data type (e.g., string) but receives a different type (e.g., array).  This often leads to runtime errors or unexpected behavior.  This example showcases how to identify and fix this using TypeScript's type system.