# Deep learning for Recommendation class

Setup instructions:

#### 1. Download the SSH key.

#### 2. Select AWS instance from the list.

#### 3. Connect to the AWS instance using the key .
``chmod 400 reco_class.pem``

``ssh -i reco_class.pem ubuntu@AWS_INSTANCE``

#### 4. Create your working directory.
``mkdir YOUR_NAME.YOUR_SURNAME``

``cd YOUR_NAME.YOUR_SURNAME``

``git clone https://github.com/bandofstraycats/reco_class.git``

``cd reco_class``         
     
#### 5. Pick a random port from 6000 to 7000.

#### 6. Start jupyter server.
``jupyter notebook --no-browser --port YOUR_PORT --ip=*``

#### 7. Open notebook in your browser.
``http://AWS_INSTANCE:YOUR_PORT/?token=YOUR_TOKEN``

#### 8. Navigate to the exercise.
``reco/DL_reco_class_exercise.ipynb``
