# Practical

1. Create a new Python file and import BertModel and BertTokenizer from the transformers library.
3. Create a variable called sentence, and assign it to a sentence, formatted as a string.
4. Create a variable called model_name , assigning the value bert-base-uncased.
5. Create an instance of the BertTokenizer.from_pretrained class, passing model_name as a parameter.
6. Pass the sentence into the tokeniser as a parameter of its encode method, and store the output in a variable called tokens
7. Print the output. Do you see any patterns in how the tokens are assigned?
8. Now pass the tokens variable into the decode method of the tokenizer. How does the output compare to the original sentence?
9. Now try altering the values in the tokens variable (for example by adding 1 to each value). Pass them through the decoder again.
