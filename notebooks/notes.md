# **Truncation (Cutting Off)**

## **Purpose**  
Determines whether to truncate the input sequence and, if so, how to do it. Most transformer models (such as BERT, RoBERTa, etc.) have a maximum input length (e.g., 512 tokens). Truncation helps handle sequences that exceed this limit.

## **Values**  

- **`False` or `'do_not_truncate'` (default):** No truncation. If the sequence exceeds the model's limit, an error may occur.

- **`True` or `'longest_first'`:** Truncate following the "longest first" principle.  
  - If you provide a single sequence: It will be truncated until it fits the maximum length (`max_length` or the model’s limit).  
  - If you provide a pair of sequences (e.g., question and context): The longer sequence will be truncated first until the total length (including special tokens like `[CLS]`, `[SEP]`) meets `max_length`. This continues until the desired length is reached.

- **`'only_first'`**: Only truncates the first sequence in a pair (or batch). The second sequence remains unchanged.

- **`'only_second'`**: Only truncates the second sequence in a pair (or batch). The first sequence remains unchanged.
