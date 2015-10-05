### Oslo Data Science Deep Learning Tutorial

These are the ipython notebooks used in the deep learning "hands-on" tutorial held at 5. october 2015.

There is also an Amazon EC2 AMI which has caffe and all dependencies installed, available [here](https://console.aws.amazon.com/ec2/v2/home?region=eu-west-1#LaunchInstanceWizard:ami=ami-dbdde9ac). Note that this AMI is available only in the Ireland Region.

Once you have the EC2 instance set up, download these files by running ```git clone https://github.com/auduno/ods-deep-learning-tutorial.git```. You can also set up an ipython notebook server on the EC2 instance by running the command ```jupyter notebook```. This allows you to access the notebooks via the url "http://0.0.0.0:8888", where you should replace "0.0.0.0" with the IP of your EC2 instance.