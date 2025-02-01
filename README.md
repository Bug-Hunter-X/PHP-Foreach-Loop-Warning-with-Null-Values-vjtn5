# PHP Foreach Loop Warning with Null Values

This repository demonstrates an uncommon error in PHP related to foreach loops and arrays containing null values.

The issue arises when a foreach loop iterates over an array that contains null values.  PHP will issue a warning in this scenario, which might not be immediately apparent and can lead to unexpected behavior in larger applications.

The bug is demonstrated in `bug.php`, and a solution is provided in `bugSolution.php`.