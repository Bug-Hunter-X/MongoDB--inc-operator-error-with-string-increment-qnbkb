# MongoDB $inc Operator Error with String Increment

This repository demonstrates a common error encountered when using the `$inc` operator in MongoDB update operations.  The error arises from attempting to increment a field using a string value instead of a numeric value.

## Problem

The provided JavaScript code shows an incorrect use of the `$inc` operator. The `field` is being incremented by the string '1' instead of the number 1. This will throw a MongoDB error.

## Solution

A corrected version of the code is provided, which demonstrates the correct way of using the `$inc` operator to increment a numeric field by 1.