# My_stratego_project


In here; a documentation and representation of how to replicate the work will be stored, commited files are downloaded from google collab and stored here for public access.



For downloading the data please refer to Strados2 on the Gravon platform, there you can manually download all the files. Remove the files that are not named "Classic", this includes "FreeClassic". After this running the content extraction file will produce a new file that you can use to run in the neural net notebook for training the graph neural network. If you haven't removed all files the content extraction should also ignore these files and remove them.
Please add the files from Strados into a folder called files and run the content extraction code first locally on your IDE, this will create 2 new files. Upload these files to google drive and add them to a folder called files in the same folder as where you will execute the google collab notebooks. Then having the directory look like mydrive -> yourproject(where you story the notebooks) -> files(where you store the data), having done this all should work accordingly.
Then, 2nd run the Strategy_analysis.ipynb in google collab, this will produce a new file with added encoded strategies from the Deepmind paper, download this file and add it to the files folder in your google drive. This file contains all the data necessary to train the models.
After running all 3 neural networks, each network will produce a .pth file at the end of the notebook, download this file and add it to the files folder in your drive. This file is the model weights and is used for evaluating the alternate deployments in the positions effects notebook. 
Run this position effects notebook to get the results for evaluating the alternate deployments. 

If all is done in the order stated above, no errors should be encountered and all results should be identical to my bachelor end project. If you'd like to read along my bachelor thesis is also on this github. 
