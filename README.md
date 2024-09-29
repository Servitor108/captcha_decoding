# captcha_decoding
predict the captcha text

What we did here in points:
 1. Extracting the image info using convolutional neural networks and pooling layers
 2. Flattening the results and feeding them to LSTM ( because it's sequential data)
 3. then use a dense nn followed by softmax ( length possible characters)
