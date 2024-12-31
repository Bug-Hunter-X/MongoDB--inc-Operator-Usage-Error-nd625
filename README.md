# MongoDB $inc Operator Usage Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.

## Problem

Incorrectly using the `$inc` operator can lead to unexpected results and errors.  This often happens when the field being incremented isn't properly quoted within the update operator.

## Solution

Always ensure that the field names you are incrementing are quoted as strings inside the `$inc` operator. This ensures that MongoDB correctly parses the update operation.

## Example

The provided `bug.js` file demonstrates the erroneous usage; `bugSolution.js` demonstrates the correct usage.
