# If your requirements.txt file is not able to install the packages, you can use these commands

! pip install datasets transformers==4.30.2
! pip install accelerate==0.20.3
! pip install --upgrade protobuf
! pip install torch==1.11.0
! pip install transformers[torch]
! pip install setuptools==68.0.0

The python interpreter required for this project is 
python_version=="3.10"


To increase the accuracy of the model you can change the number of epochs (train on large number of epochs)
This argument is declared in- 
   src - fine_tuning - preprocessing - preprocessing.py
                                     (num_train_epochs=0.00000002)
