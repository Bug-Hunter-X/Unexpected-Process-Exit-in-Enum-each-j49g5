# Elixir Enum.each Unexpected Exit

This repository demonstrates a common error encountered when using `Enum.each` in Elixir. The code terminates early due to an improper use of `Process.exit` within the `Enum.each` anonymous function.

The `bug.ex` file shows the buggy code that results in early termination, while `bugSolution.ex` provides a corrected version.