# Plagiarism-Detector-with-Hashing-Techniques
I implement a plagiarism detector which uses two differing hashing storage methods and compare their relative time complexities.

My repository consists of two plagiarism detectors which use (1) rolling hashing and (2) linear probing to store items from a text-based input. A small terms list below provides definitions for both methods of storage. The subsequent methods within the Hash Table classes can determine all substring matches between two or more texts and can provide a matching percentage to quantify the extent to which the texts are plagiarized.

I hope you enjoy the code! :)

**Terms:**

**Rolling Hashing:** is a data storage technique which employs recursion to store multiple components of input within specified indexes of an array. Specifically, rolling hashing uses a hash function which produces an index value for each component of input and stores it in the corresponding index. One array index can have multiple inputs in a nested array.

**Linear Probing:** is a collision resolution technique in data storage which, when encountering a collision where there is already input in the hash function's returned index, moves linearly along the array until it finds an empty space for the input component to be stored.
