# Elixir List Modification in Enum.each

This example demonstrates a common pitfall when working with lists in Elixir: attempting to modify a list while iterating over it using `Enum.each`.  Because Elixir lists are immutable, modifying the list within the `Enum.each` loop will not have the desired effect.

The `bug.exs` file shows the incorrect approach. The solution in `bugSolution.exs` offers a correct way to achieve the intended list modification.