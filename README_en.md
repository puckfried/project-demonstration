# Exercise – Mini Kiosk

Complete the steps one after another and test your program after each step. Program a mini kiosk with this menu:

- `1` – Water: 1.50 euros
- `2` – Coffee: 2.80 euros
- `3` – Show total price
- `4` – Quit

You can see one possible result here:

![Kiosk animation](./kiosk-vorlage.gif)

Work on your own branch and push it to GitHub when you have finished your work.

## Basics

1. Display the menu again after each selection.
2. End the program with `break` when the user selects `4`.
3. When the user selects `1`, add the price of water to the total price.
4. When the user selects `2`, add the price of coffee to the total price.
5. When the user selects `3`, display the current total price.
6. For all other inputs, display an error message and use `continue` to start the next loop iteration.
7. Display the final total price after the program ends.

You are finished when:

- several products can be ordered one after another
- the total price is calculated correctly
- invalid inputs do not end the program
- selecting `4` ends the loop in a controlled way

## If You Need Help

- Users make a selection by entering something like `"1"` or `"4"`.
- Use `if`, `elif`, and `else` for the different paths.
- The total price must be created before the loop. When a product is added, its price is added to the total price.
- First, test only how to quit the program. Then add one selection after another.

## Extras

- Count how many products were ordered.
- Add an option that resets the total price.
- Set a budget and display a warning when the total price exceeds it.
- Format the total price with two decimal places.
