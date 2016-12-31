# File signature evaluator for .Net 3.5
Devides binary file into equal blocks and evaluates SHA-256 hash for each block
(file name and block size are specified by command line arguments).
Output hash values as hex stings to console.

Algorithm uses RAM and CPU wisely (uses threads pool and limited read and write buffers).
