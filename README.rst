In the wake of current corona virus pandemic situation, it is necessary for all to wear a mask to thwart the event of cross-contamination,

So, Me and Mohak Parekh (peer at DD UNIVERSITY), decided to work on a project of Mask Detection System based on Machine Learning and OpenCV, which recognizes whether the person has worn mask or not, all task is mechanized, no human interaction is required.

We trained 101 layers deep convolutional neural network, Resnet-101 on the data we gathered and integrated it with Flask for building web application.

This system can be applied and can be utilized at Banks, Offices, Malls, Restaurants and other public places.


`Output <https://github.com/harshnagoriya/FaceMask-Detection-System/blob/master/output/output.mp4>`_!

pip-update-requirements
=======================

Update/install the packages in a ``requirements.txt`` file.

Usage
-----

Dataset is generated by both of the `creators <https://github.com/harshnagoriya/FaceMask-Detection-System/blob/master/creators.rst>`_ by putting lots of efforts, hence, it is not uploaded here, you need to ask to the `creators <https://github.com/harshnagoriya/FaceMask-Detection-System/blob/master/creators.rst>`_ for dataset! 

Give pip3 your ``requirements.txt`` file and it updates all your packages to the latest versions.

build model by compiling FinalX Jupyer Notebook file, save .pth file to preferrable path

Address .pth file to app.py and write in console::

	FLASK_ENV=development FLASK_APP=app.py flask run
	
After writing this in console project is deployed on localhost, port number 5000 (port number may differ)

Go to the browser and open::
	
	127.0.0.1:5000/






