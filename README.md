<h1>IOSD ML Project</h1></br>
I am Samyak Jain and this is my submission for ML project of IOSD Junior Council.</br>
I have implemented the SVM kernel from Sci-Kit learn library.</br>
I have also implemented a pytorch network as a binary classifier.</br>
<b>Note: I have shown visualizations only in First notebook, was not able to do it in Second Notebook due to Kaggle limitations.</br>

I have linked both the kaggle notebooks to Github, please visit the kaggle to run it.</br>
Leaving the link to both the kaggle notebooks.</br></br>

Notebook 1 - https://www.kaggle.com/code/samyak15jain/notebookbadffc0c63</br>
Notebook 2 - https://www.kaggle.com/code/samyak15jain/pytorch-basic-ann</br></br>


Since the dataset is highly unbalanced I have also used balancing parameter in SVM and assigned class weights in Pytorch Neural Netwrok using Weighted Random Sampler.
</br></br>

<h3>Feature Engineering</h3></br>
More features such as Mass, Volume and Impact Energy are found to have an effect on decision making process whether a Near Object Earth is hazardous or  not. This was concluded after going through several academic papers and articles online. One such paper is referenced in the notebook.
</br> Reference
</br> The near-Earth objects and their potential threat(Research Paper)
 </br>DOI 10.1007/s00159-013-0065-4
</br></br>

<h3>Notebook 1</h3></br> 
In this notebook I have implemented Support Vector Machine from the Scikit library. I have used different kernels in the model such as Linear, Polynomial, Rbf and Sigmoid.
</br>I have used Grid parameters for the best selection of parameters depending upon accuracy.
</br>Grid Parameters included are {C,gamma,degree, kernel}.</br>
Used Intel(R) Extension for Scikit-learn* for faster processing of SVM.</br>
I have also scaled the data for faster processing </br>

<h4>Validation</h4>
I have calculated the precision, accuracy, f1 score for all the kernels with their best paramters according to the Grid paramters.</br>
Finally a perfomance report and a confusion matrix is generated for evaluation of the model.

<h3>Notebook 2</h3>
Here I have implemented a Pytorch Network using ANN.</br>
I have created 5 layers with 250 neurons each and used Pytorch's Dataloader to load the dataset</br>
Since the data was highly imabanced, I had to run the model for 720465 epochs(🙀) and a very low learning rate.</br>
I also manually assigned the classes their weights to make the data a bit more apropriate for training.</br>

<h4>Validation</h4>
I have calculated the accuracy of the model using a simple loop and counting the number of correct predictions.</br>
I have used the CUDA platform of NVIDIA GPUs for parallel processing.
</br>
</br>
Thanks For Reading!




