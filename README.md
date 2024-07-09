# Removing_Spl_chr
Removing Special Characters in Python
#here is the code

import re

def remove_special_characters(text):
    # Replace all non-alphanumeric characters with an empty string
    cleaned_text = re.sub(r'[^A-Za-z0-9\s]', '', text)
    return cleaned_text

# Example usage
text = "Hello, World! This is a test string with special characters: @#^&*()"
cleaned_text = remove_special_characters(text)
print(cleaned_text)
