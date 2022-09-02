<h1>Notebook 1</h1>
<p> In this notebook I have classified Nearest Earth Objects as Hazardous and Non Hazardous. I have used classification using SVM to train my model. I have utilised
  grid parameter function of Scikit learn library to find out the best parameters foe the highest accuracy possible.</p>
  <h2>Plotting</h2>
  <p>I have made use of different plotting libraries such matplotlib, seaborn and plotly to visualize the data. However the plotly library had to be removed later as it was not showing in the uploaded version of github.
  I have included cluster maps, heat maps, frequencies et cetera to help better understand the data</p>
  <h2>Data</h2>
  <p>I have also used Feature engineering to further improve the accuracy of model by creating new features such as mass, velocity, kinetic energy. This allowed the model to train on more number of features.
  Also I had to drop several features such as id, sentry_object and orbiting body as they were not important to train the model.</p>
  <h2>Kernels</h2>
  </p>I have used several kernels for Support Vector Machine such as Linear, polynomial, rbf, sigmoid. They basically decide how the hyperplane should be divided to segregate the data with different features.
  Further, I have tried to iterate over different values of C to make sure my model does not overfit the data.</p>
  <h2>Loading Data</h2>
  <p> I have used Scikit train_test_split library to load the dataset. I have also scaled the data for faster processing and have balanced the data. Additionaly  I have used Intel's Library to further reduce the computation time.
  </p>
  
  <h2>Validation</h2>
  <p>I have generated perfomance reports comprising of accuracy scores, f1 scores, precision to validate my model. I have also plotted a confusion matrix for each grid parameter to better understand my model.
