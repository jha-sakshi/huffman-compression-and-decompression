Theory
-------
 Huffman compression is based on huffman coding technique. The huffman coding creates an optimal binary tree that is constructed based on frequency of an item/character in a file.

 Let's take an example of a file or string containing data like "AAABBCAAADDFFAAAADCCCDAADDDAAACGAAACACA"
![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/844ea8db-4517-45ba-971f-1d7c110bb52f)



  The above following data will generate a binary tree starting from the characters having the lowest frequency, and construct till we use all the characters as follows:

![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/d06beef8-0c3e-463b-b818-c954a95d9cef)


![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/68024a33-3ac8-4cd7-adb8-8a097acbbdb4)


![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/0d00a3c6-21ed-4b93-a772-f26c99966111)

                                                                              
![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/bb1f28ed-037d-4d75-a895-bd3877063e12)

                                                                     
![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/fe740f55-cff9-4412-b551-683c77abeccf)

                                                         
![image](https://github.com/jha-sakshi/huffman-file-compression/assets/95759285/4d3b6755-f59e-47ba-a1a3-f3de1c4aec0a)


Hence the resultant data is stored as binary written as '000101110110001001001010010100000010011111110000100100100000111010100011011000000', which has 75 bits plus 5 digits appended to
round off the remaining bits while storing in the file.
