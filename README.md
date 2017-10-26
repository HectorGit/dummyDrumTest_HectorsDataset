# dummyDrumTest_HectorsDataset
I created my own set of samples (drum-samples) by recording a drum. Tested openNN with that.

This is a close clone to https://github.com/HectorGit/dummyDrumTest repository.
The main change is that I used the data set I created to test the NN
(Had around 150 sounds for each of 3 classes:)

Class 1 = Center    
Class 2 = HalfEdge    
Class 3 = Rimshot     

Classification Result is in latestResults/proceeds/confusion.dat
For your convenience I put it here:

22 0 0                             
1 28 0     
2 1 36 

So we can see that the accuracy is: correct/total = 86/90 = 0.95 or 95%
