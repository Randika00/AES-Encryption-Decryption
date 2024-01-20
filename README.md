## AES-Encryption-Decryption
<b>The Advanced Encryption Standard (AES)</b>

An algorithm that uses the same key to encrypt and decrypt protected data. Instead of a single round of encryption, data is put through 
several rounds of substitution, transposition, and mixing to make it harder to compromise.That means it takes 128 bits as input and outputs 
128 bits of encrypted cipher text as output. AES relies on substitution-permutation network principle which means it is performed using a 
series of linked operations which involves replacing and shuffling of the input data. 

The number of rounds depends on the key length as follows : 

     *  128 bit key – 10 rounds
     *  192 bit key – 12 rounds
     *  256 bit key – 14 rounds

<i>Encryption - AES considers each block as a 16 byte (4 byte x 4 byte = 128 ) grid in a column major arrangement.</i>   

     [ b0  | b1  | b2  | b3  ]         [ b0  | b1  | b2  | b3  ]
     | b4  | b5  | b6  | b7  |    ->   | b5  | b6  | b7  | b4  |
     | b8  | b9  | b10 | b11 |         | b10 | b11 | b8  | b9  |
     [ b12 | b13 | b14 | b15 ]         [ b15 | b12 | b13 | b14 ]

 Decryption is the process of converting an encrypted message back to its original (readable) format. The original message is 
 called the plaintext message. The encrypted message is called the ciphertext message.In decryption, the system extracts and 
 converts the garbled data and transforms it to texts and images that are easily understandable not only by the reader but also
 by the system. Decryption may be accomplished manually or automatically. It may also be performed with a set of keys or passwords. 




[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Workflow](https://img.shields.io/github/actions/workflow/status/Group-52/DineMate-2.0/deploy.yaml?branch=main&style=flat)

