# -Teachable-Machine

Step 1 Train the model:

Went to Teachable Machine and started a new Image Project then Standard image model.
Created 2 classes: dogs and cats, and added sample of 6 images for each.
Clicked Train Model.
Tested it to check it was predicting correctly.

Step 2  Export the model:

Clicked Export Model.
Selected the TensorFlow tab then Keras format.
Clicked Download my model, which gave a file that contains keras_model.h5 and labels.txt.

Step 3  Set up the environment using Anaconda:

Went to Anaconda Navigator and created a enviroment and named it (smart methods2),
then used the right python version which meets the teachable machine 3.10.20,
then installed the requirments (tensorflow , pillow , numpy) using cmd.

step 4 use python and run the code:

I copy and pasted the given code (from the results of the teachable machine) and edited it by changing one of the code lines to meet the path of the photo that i want to test.

After editing and running the code using ( activate test_code) i got the results which happened to be correct
