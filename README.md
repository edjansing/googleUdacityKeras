# googleUdacityKeras
Exercises from the Udacity/Google "Deep Learning" course, modified for Keras.

You must have Keras (https://keras.io) installed.  I highly recommend installing Keras in a virtual environment, such as Anaconda, so as to leave your system Python unmodified.  This is particularly true for Linux and Mac machines.  The backend for Keras is not critical; if you install Keras from pip, you'll get Theano by default (make sure Theano isn't already installed; if it is, uninstall it first, then pip keras).  Setting up TensorFlow as the backend is not difficult.

If you have a Mac with a non-NVIDIA GPU, don't bother trying to get OpenGPU to work.  As of Oct 2016, it isn't stable enough to work with Mac GPUs.  Instead, consider setting up your own Amazon Web Service EC2 GPU instance.  It's easy and not horribly expensive.  Just don't leave it running all the time (you get charged for that computer time, even if you aren't running anything currently; shut down your instance if you're not using it)!

