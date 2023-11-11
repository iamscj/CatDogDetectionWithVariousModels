# Building and Training Neural Networks for Image Classification

## Task 2: Transfer Learning with VGG16 Model

1. **Download Pre-trained Weights for VGG16 Model:**
   - Download the weights of the VGG16 network trained on the ImageNet dataset.

2. **Construct Transfer Learning Model using VGG16:**
   - Build a model by adding two fully connected layers to the VGG16 model.
   - Use the downloaded weights for initialization.

3. **Fit the Model with Custom Dataset:**
   - Train the model using a generator on the Cats and Dogs dataset.
   - Utilize a GPU for faster training if available.

4. **Evaluate Model Accuracy:**
   - Evaluate the accuracy on both the training and validation datasets.
   - Plot graphs for loss and accuracy over epochs.
   
5. **Inference on Custom Image:**
   - Develop a function for model inference on custom cat or dog images.
   - Test the performance with a custom image and display the predicted class.

## Task 3: Transfer Learning with ResNet Model

1. **Build and Fit Transfer Learning Model using ResNet:**
   - Design a ResNet-based neural network architecture.
   - Train the model on the Cats and Dogs dataset with data augmentation.

2. **Evaluate Accuracy and Plot Graphs:**
   - Evaluate accuracy on the test data.
   - Plot graphs for loss and accuracy over epochs.

3. **Inference on Custom Image:**
   - Develop a function for model inference on custom cat or dog images.
   - Test the performance with a custom image and display the predicted class.

## Task 4: Building and Training UNet-based Model (Binary Classification)

1. **Define UNet Architecture:**
   - Implement Encoder, Bottleneck, and Decoder blocks.
   - Assemble the UNet model with specified in/out channels.

2. **Loss Function and Optimizer:**
   - Use Binary Cross-Entropy loss.
   - Implement the Adam optimizer.

3. **Train the UNet Model:**
   - Train the UNet model on the training dataset.
   - Print the model summary.

4. **Evaluate Accuracy on Validation Dataset:**
   - Evaluate accuracy on the validation dataset.
