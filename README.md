

This program uses the textwrap module's wrap() function which will split the given text into a list of lines, 

it takes the width as the parameter and make sure that no words are broken.

Then we have two list left_justified and right_justified where left_justified will hold all the 

lines left justified and right_justified will hold all the lines right justified using the ljust() and rjust() function


# Unit test
text = "This is a sample paragraph that we want to justify."
width = 20

print(justify_text(text, width))

Output:

(['This is a sample ', 'paragraph that we ', 'want to justify.'], ['    This is a sample ', 'paragraph that we ', 'want to justify.   '])
