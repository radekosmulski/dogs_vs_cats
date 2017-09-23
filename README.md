You can read more about this repository [here](https://medium.com/@radekosmulski/can-we-beat-the-state-of-the-art-from-2013-with-only-0-046-of-training-examples-yes-we-can-18be24b8615f)

Steps to reproduce:
1. Download the data from the dogs-vs-cats Kaggle competition into the root of the directory.
2. Unzip it (it should reside in `train` directory under root of the repository)
3. Run all the cells in the notebook

The results may vary but they should be within reason. Among this being sensitive to how lucky we get on the draw of the 6 random images, the 41 epochs of training sometimes are not enough.
