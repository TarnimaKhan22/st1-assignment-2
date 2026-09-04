PART H
Reflection

Before using AI, I had already built the basic version of the program myself. Collecting patient, practitioner and time details with simple input() statements and printing them with an f-string. It worked, but it was limited to one hardcoded flow, with no structure for handling multiple appointments or incorrect input.

AI helped me understand how to organise the program using functions and a list of dictionaries instead of separate variables, and why this structure scales better. It also helped me realise through the Part F testing that my original version had no error handling. I had not considered this until we tested blank and None inputs and saw that they could cause problems instead of being handled safely.

AI also made assumptions that inputs would be valid and in the correct format. For example, it did not initially consider blank values, spaces or incorrectly formatted information. Testing these cases helped me understand why input validation is important.

To verify the output, I ran some tests myself and reviewed the other results shown by AI, checking that the error messages and program behaviour matched the expected results.

The engineering work that remained for me was deciding what to keep, choosing the single improvement, simplifying the structure and making the final decisions that AI could not make independently.