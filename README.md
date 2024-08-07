1. The source code includes the algorithms implemented using ArrayList, BitSet and HashSet. The implementation with ArrayList is the fastest one.
2. To run the algorithm, the format of parameters is : input file name, the size k, the running time threshold, algorithm name . An example: inf-power.mtx 4939 600 TopDown
3. The algorithms were implemented recursively. To avoid stackoverflow issue, we may set VM arguments: -Xss10M. 
4. The input files are in the folder 'graphs', and the output files are in folder 'outputs'.
5. SimpleForwardSizeKUsingArrayList,SimpleSizeKUsingArrayList,VariantSimpleSizeKUsingArrayList and TopDownEnumerationSizeKUsingArrayList correspond to the SimpleForward,Simple,VSimple and TopnDown algorithms in the paper titled Novel Algorithms for Efficient Mining of Connected Induced Subgraphs of a Given Cardinality.
6. KDeltaDelayEnumeration.java is the algorithm with a delay of $O(k\Delta)$.
