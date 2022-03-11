# disable-logging-output-from-TensorFlow
Disable all logging output from TensorFlow

To disable all logging output from TensorFlow, set the following environment variable before launching Python:
import os
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '2'

You can also adjust the verbosity by changing the value of TF_CPP_MIN_LOG_LEVEL:

0 = all messages are logged (default behavior)
1 = INFO messages are not printed
2 = INFO and WARNING messages are not printed
3 = INFO, WARNING, and ERROR messages are not printed
