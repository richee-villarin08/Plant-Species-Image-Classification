[##ImageDataset](https://drive.google.com/drive/folders/1vsTiDxKe8xncutBzwygqgZAg8cbZ4fZN?usp=drive_link)

#Reflection Questions:

Answer the following questions based on your experience:
1. How did the number of images per class affect your model’s accuracy?
    >> Increasing images per class boosted accuracy by preventing bias, though limited samples for rare flowers often led the model to "guess" more common species.
2. Which plant species were most commonly misclassified and why?
    >> vanda and dendrodium were most frequently confused because their overlapping color gradients and closed-bud shapes appear nearly identical to a standard CNN.
3. How did changing the epochs, batch size, or learning rate affect the training results?
    >> High learning rates caused accuracy to oscillate wildly, while increasing epochs without regularization led the model to memorize specific background dirt instead of the flowers.
4. What challenges did you encounter during dataset collection and labeling?
    >>Dataset collection was hindered by intra-class variation (like red vs. white roses) and "noisy" labels where human error misidentified look-alike species during sorting. 
5. If you were to improve your model, what specific changes would you make and why?
    > I would use pre-trained model (like MobileNetV2) because it already "knows" what shapes and colors look like from millions of other photos, which saves time and makes the flower identification much more accurate than starting from zero.
