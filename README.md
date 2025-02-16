# PHP Type Juggling Bug

This repository demonstrates a common issue in PHP programming related to type juggling and the implications of using loose comparison (==) versus strict comparison (===).

Loose comparison (==) can lead to unexpected results due to PHP's automatic type coercion.  Strict comparison (===), on the other hand, checks both value and type, preventing these surprises.

The `bug.php` file showcases the problem, and `bugSolution.php` provides the corrected code.