Student Name : Nitheesh Reddy Pabbangari
Student ID; 700774002


q2.2_minibpe.ipynb

This notebook contains the Mini-BPE implementation for Question 2.2.

The program uses the class toy corpus:

```text
low low low low low
lowest lowest
newer newer newer newer newer newer
wider wider wider
new new
```

The code first counts the word frequencies and adds `_` as the end-of-word marker. It then starts with individual characters, counts neighboring token pairs, and repeatedly merges the most frequent pair.

The notebook prints the BPE merges and vocabulary changes and then uses the learned merges to segment words such as `new`, `newer`, `lowest`, `widest`, and `newestest`.

This shows how BPE can create reusable subword tokens instead of storing every complete word separately.

q2.3.1.py

This file contains the BPE implementation for Question 2.3.

The training paragraph used in this program is:

 “Tell your heart that the fear of suffering is worse than the suffering itself. And that no heart has ever suffered when it goes in search of its dreams, because every second of the search is a second's encounter with God and with eternity.”

The program first extracts the words from this paragraph and counts their frequencies. It then represents each word as individual characters with `_` as the end-of-word marker.

BPE is trained for 30 merges. After training, the program displays the five most frequent merges and the five longest subword tokens. It also segments five words from the paragraph: `suffering`, `eternity`, `encounter`, `dreams`, and `heart`.

q5.ipynb

This notebook contains the tokenization work for Question 5.

The program uses a telugu paragraph about **weather, people walking in a park, children playing and telling stories, and having tea with friends**.

It compares three approaches:

 Naive space-based tokenization
 Manually corrected tokenization
 NLP tool-based tokenization

The main difference is how punctuation is handled.
