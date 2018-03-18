### Instructions for doing the project on Google Colaboratory

Google colaboratory now offers free GPU resources (March 2018), which means you don't need to worry about getting a GPU when you try to build a deep neural network !     

Using Google colaboratory requires that you have a Google account. If you don't have one, sign up for one [here](https://accounts.google.com/SignUp?hl=en).  Then you can access Google colaboratory [here](https://colab.research.google.com).     

Let's first create a new Jupyter notebook to upload the project files. You'll have to upload Jupyter notebook and other helper files separately. First in code cell, type in the following :    

    from google.colab import files

    uploaded = files.upload()
    
In the output of the cell, a `choose file` button will pop up. Click on that button and upload `helper.py` and `problem_unittests.py`. You can verify that they're successfully uploaded by typing this in another code cell. 

    !ls    

Here, exclamation mark means eecuting command in shell.         

The in the Toolbar choose `File --> Upload notebook` and upload the project file `First_convolutional_neural_network.ipynb`. After the upload is finished, you'll be taken to this notebook. Then in the Toolbar, choose `Runtime --> Change runtime type`. Choose Python 3 as the runtime type and GPU as hardware accelerator, and you're good to go !     