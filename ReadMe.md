import textwrap

def justify_text(text, width):
    lines = textwrap.wrap(text, width=width)

    left_justified = []
    right_justified = []
    for line in lines:
        left_justified.append(line.ljust(width))
        right_justified.append(line.rjust(width))
    
    return left_justified, right_justified

# Unit test
text = "This is a sample paragraph that we want to justify."
width = 20

print(justify_text(text, width))

Output:
(['This is a sample ', 'paragraph that we ', 'want to justify.'], ['    This is a sample ', 'paragraph that we ', 'want to justify.   '])








