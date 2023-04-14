# Speech-Emotion-Recognition

Emotional state identification based on analysis of vocalization is a challenging subject in the field of Human-Computer Interaction (HCI). A wide range of research approaches has been used and recent research has suggested the use of deep learning algorithms. as potential alternatives to the approaches that are traditionally used in SER. The objective of this project is to utilize Deep Neural Network (DNNs) to recognise human speech emotion . First Mel – Frequency cepstral coefficient (MFCC) are extracted from raw audio data then speech features extracted were fed into DNN to train the network. The trained network was then tested onto a set of labelled emotion speech audio and the recognition rate was evaluated. Based on the accuracy rate of MFCC, number of neurons and layers are adjusted for optimization. Beyond the scope of previous researches, this project emphasize on speech based output instead of text based results. 

### Dataset:
<a href="https://abes365-my.sharepoint.com/personal/shishir_20b1531118_abes_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fshishir%5F20b1531118%5Fabes%5Fac%5Fin%2FDocuments%2FCREMA%2DD">Click here to get CREMA-D dataset.</a><br>
<a href="https://abes365-my.sharepoint.com/personal/shishir_20b1531118_abes_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fshishir%5F20b1531118%5Fabes%5Fac%5Fin%2FDocuments%2FRAVDESS%20Dataset">Click here to get RAVDESS dataset.</a><br>
<a href="https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess">Click here to get TESS dataset.</a><br>

### Built With::
<ul>
  <li>Python - Programming Language</ii>
    <li>Scikit-Learn - Machine Learning Library for Python</ii>
    <li>TensorFlow - Open Source Machine Learning Framework</li>
    <li>Librosa - Python Package for Music and Audio Analysis</li>
</ul>

### To use this project, follow these steps:
<ol>
  <li>Clone the repository: git clone https://github.com/shishir-dwi/Speech-Emotion-Recognition</li>
  <li>Open any `.ipynb` file in Jupyter Notebook or any other compatible software.</li>
  <li>Follow the instructions in the Notebook to run the code and train the model.</li>
  <li>Evaluate the performance of the model using the metrics generated in the Notebook.</li>
</ol>

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### License
This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) - see the [LICENSE](LICENSE) file for details.
