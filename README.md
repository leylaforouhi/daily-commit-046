def count_sentences(texT):
    return text.count('.') + text.count('!') + text.count('?')

if __name__ == "__main__":
    sample = "GitHub is great. I code daily! Do you?"
    print(f"Number of sentences: {count_sentences(sample)}")
