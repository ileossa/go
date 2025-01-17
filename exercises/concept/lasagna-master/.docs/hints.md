# Hints

## 1. Estimate the preparation time

- Use the `len()` keyword to determine the number of layers (length of the layers array).

## 2. Compute the amounts of noodles and sauce needed

- First, set up two variables to track the amount of noodles and sauce.
- Use a for loop to iterate through the layers.
- If you encounter a `'noodles'` or `'sauce'` layer in your loop, increase the amount stored in the respective variable accordingly.

## 3. Add the secret ingredient

- Revisit [slices][concept-slices] to find out how to retrieve an element from an slice and how to add something the end of a slice.
- The index of the last element in an array `a` is `len(a) - 1`.

## 4. Scale the recipe

- First make a new slice of the same size as the input slice
- Use a [for range loop][concept-range-iteration] to iterate through the input slice and generate the output slice

[concept-conditonals-if]: /tracks/go/concepts/conditionals-if
[concept-slices]: /tracks/go/concepts/slices
