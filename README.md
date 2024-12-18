# Unexpected Container Collapse with :last-child and Floated Elements

This repository demonstrates an uncommon CSS bug related to the interaction between the `:last-child` pseudo-class, floated elements, and container height.  When using `:last-child` with `clear:both` on floated elements, unexpected container collapse can occur if the number of elements isn't a multiple of the number of elements per row.

The `bug.css` file contains the problematic CSS.  The `bugSolution.css` file provides a solution using clearfix.