# Improve the ability of SyncMap

Improving the ability of SyncMap by the adaptive learning rate.

## The point of this way

In SyncMap nodes update the position by MSE learning. And in orignal algorithm which updates the nodes position with the unchanged learning rate. In the learning We hope the learning rate can be smaller in the end stage so that the node can get centralization. So if we want to improve the learning ability of SyncMap, We can make the learning rate be adaptive in the learning.In the proposal way with the epochs incrase, the learning rate get smaller.

## Results

I have made the experiment with the FixedChunkTest benchmark(The orignal resource code in the github which have no comment and have much mistakes, I have try to fix them, But only the FixedChunkTest benchmark can excuted). And in the results on FixedChunkTest the accuracy is 60% which is higher than orignal way 50%. The results which is stored in the github named [Results.xlsx].
