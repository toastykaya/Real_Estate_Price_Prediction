# Problem Statement
- Law Enforcement needs an easy way to identify suspicious/fraudulent housing to better narrow  down where criminal activity may be taking place
## Tools/Method
- Auto-encoder:
    A type of neural network that learns how to encode and decode the data it is trained
    on, in the process of doing so it learns the most common/crucial features that make up
    a real-estate listing. When it tries to do this on an anomalous entry it's prediction
    will be worse (it takes the MSE of the test/correct data - the MSE of it's decoded
    value) thus if the prediction score is bad the entry is likely an anomaly
- Bottleneck structure for nodes
- Multi Layer Perceptron
- TensorFlow/Keras
- https://www.tensorflow.org/tutorials/generative/autoencoder
## Steps
- Separating anomaly entries from normal entries
- Training model on normal entries
- Classify a property as anomalous if it is 1 standard deviation from normal training examples
- Building UI to interact (gradio?)
## Resources
- https://blog.keras.io/building-autoencoders-in-keras.html
- https://blog.tensorflow.org/2020/04/how-airbus-detects-anomalies-iss-telemetry-data-tfx.html?_gl=1*15qw24g*_ga*NzYxNTc3MjgxLjE3NjM5NDcxNTM.*_ga_W0YLR4190T*czE3NjQwNTM0NjEkbzQkZzAkdDE3NjQwNTM0NjQkajU3JGwwJGgw
- https://anomagram.fastforwardlabs.com/#/
- https://www.deeplearningbook.org/contents/autoencoders.html
- 

