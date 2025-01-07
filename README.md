This repository demonstrates a common error in VHDL: integer overflow in a counter. The `counter_bug.vhdl` file contains the buggy code.  The `counter_solution.vhdl` file provides a corrected version that prevents overflow.

The bug arises from the lack of a check to prevent the counter from exceeding its defined range (0 to 15). This can lead to unpredictable results or simulation errors.

The solution incorporates a modulo operation to ensure the counter wraps around correctly when it reaches the maximum value.  This ensures robust and predictable behavior.