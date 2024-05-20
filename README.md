
def count_words(text):
    # Split the text into words based on whitespace
    words = text.split()
    # Return the number of words
    return len(words)

# Main program
if __name__ == "__main__":
    # Get input from the user
    text = input("Enter a text: ")
    # Count the number of words
    word_count = count_words(text)
    # Print the result
    print(f"The number of words in the given text is: {word_count}")
