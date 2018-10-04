Excel
=====

Cell referencing
------

`B3` is a *relative* reference. If the formula containing the reference is copied somewhere else the reference is updated accordingly. To fix a row or column reference add a `$` before the row or column label. `B$3` relatively references the column `B` but absolutely references the row `3`. An absolute reference does not change if the formula is copied somewhere else. 

<!---
<question>How do you absolutely reference a cell in an excel formula?</question>
<answer>Prefix the row, column or both with `$`</answer>
--->
