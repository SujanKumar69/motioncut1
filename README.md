# motioncut1
# word count in a sentence
def count_words(sentence):
    if not sentence:
        print("The input is empty. Please enter a valid sentence.")
        return

    words = sentence.split()
    word_count = len(words)
    print(f"The number of words in the sentence is: {word_count}")

sentence = input("Enter a sentence: ")
count_words(sentence)
