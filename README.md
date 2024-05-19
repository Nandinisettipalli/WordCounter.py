# Word_Counter.py
def count_words(text):
    words = text.split()
    return len(words)

# Example usage:
sentence = "Hello, how are you?"
word_count = count_words(sentence)
print("The number of words in the sentence is:", word_count)

