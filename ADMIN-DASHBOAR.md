# Getting Started

Now that you have successfully installed DIGITS, this guide will teach you the basics of how to use it.
By the end, you will have trained a Caffe model to recognize hand-written digits.
We will be using the [MNIST handwritten digit database](http://yann.lecun.com/exdb/mnist) as our dataset and [LeNet-5](http://yann.lecun.com/exdb/lenet/) for our network.
Both are generously made available by Yann LeCun on [his website](http://yann.lecun.com/).

## Download the data

Use the following command to download the MNIST dataset onto your server:

```sh
$ python -m digits.download_data mnist ~/mnist
Downloading url=http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz ...
Downloading url=http://yann.lecun.com/exdb/mnist/train-labels-idx1-ubyte.gz ...
Downloading url=http://yann.lecun.com/exdb/mnist/t10k-images-idx3-ubyte.gz ...
Downloading url=http://yann.lecun.com/exdb/mnist/t10k-labels-idx1-ubyte.gz ...
Uncompressing file=train-images-idx3-ubyte.gz ...
Uncompressing file=train-labels-idx1-ubyte.gz ...
Uncompressing file=t10k-images-idx3-ubyte.gz ...
Uncompressing file=t10k-labels-idx1-ubyte.gz ...
Reading labels from /home/username/mnist/train-labels.bin ...
Reading images from /home/username/mnist/train-images.bin ...
Reading labels from /home/username/mnist/test-labels.bin ...
Reading images from /home/username/mnist/test-images.bin ...
Dataset directory is created successfully at '/home/username/mnist'
Done after 16.722807169 seconds.
```

See [Standard Datasets](StandardDatasets.md) for details about this script.

## Using the Webapp

![Home page](images/home-page-1.jpg)

### Logging in

Click on `Datasets > New Dataset > Images > Classification`.
This will lead you to the login page:

> NOTE: there is no authentication - you don't even need a password.
> This is a utility feature, not a security feature.

![Login](images/login.jpg)

### Creating a Dataset

After logging in, you will be brought to the "New Image Classification Dataset" page.

![New dataset](images/new-dataset.jpg)

While the job is running, you should see the expected completion time on the right side:

![Creating dataset](images/creating-dataset.jpg)

![Home page with dataset](images/admin-dashboard/home-page-1.jpg)

### Training a Model

![New model](images/admin-dashboard/home-page-1.jpg)

While training the model, you should see the expected completion time on the right side:

![Training model](images/admin-dashboard/home-page-1.jpg)


