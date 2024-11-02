Test the effectiveness of EWC on CIFAR-10

1. Split CIFAR-10 into two groups: animal, machine
2. Use a simple CNN network trained on animal train data as baseline
3. Train the CNN model on machine train data, assumably getting bad accuracy on animal test data
4. Train the model with EWC on machine train data, getting a slightly better accuracy on animal test data
