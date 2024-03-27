# Notebook Instructions of Task 1
Because the previous assignments I used Kaggle notebooks to be able to use the GPU device, I continued to use a notebook to better document my code and to make it more easily shareable. However, with this assignment, you can also run it on your machine. 
The version/structure in the GitHub differs so that when you download it, you can run it on your machine. However, I've also provided instructions for how to take the downloaded GitHub files and turn it into a Kaggle project.

# Run on Kaggle
While everything should be able to run using my [Kaggle notebook link](https://www.kaggle.com/code/alexstvn/stevenson-assignment3-task1), here are the steps to make your own Kaggle notebook using the GitHub repository files.

 1. Create a new Kaggle project.
 2. Using **File > Import Notebook**, import the file `stevenson_assignment3_task1.ipynb`.
 3. Import the images by creating a new Dataset.
	1. Go to **Upload Input > Upload Dataset**
	2. Select all three images in the `images` folder.
	3. Label the dataset as `hw3img`.
4. Update the `img_folder` parameter in `parse_args` to be `/kaggle/input/hw3img/` instead of `/images/`.


# Run on your local laptop

