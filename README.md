# 2019 Deep Learning Fundamentals and Applications in Medical Informatics Workshop

My name is [Ahmad Tafti](http://aptafti.github.io), and I have the honor to serve as a speaker at [Deep Learning Fundamentals and Applications in Medical Informatics](https://web.cvent.com/event/472ac73b-360b-4c5a-a45d-d14cc0249321/summary), which is being held in [Northwestern Mutual Cream City Labs](https://innovation.northwesternmutual.com/cream-city-labs/), April, 5-6, 2019.  

I will be covering two topics, including: <strong> 1) AI and deep learning; what and why? </strong> and <strong> 2) Deep CNN architectures and their applications in medical image analysis </strong>.  The PDF files of these topics are available within the current GitHub repository. I am trying my level best to document everything around my talks within this GitHub repository. 

##  Hands-on-practice (Python, TensorFlow, Keras)
The talk in Deep CNN architectures will include a hands-on-practice on anomaly detection of chest x-ray images using a publicly and freely available dataset of [chest x-rays](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community). We, together, will combine several deep CNN architectural models to do the task in an ensemble fashion. We will look at the work as a classifiocation problem, meaning that we will classify different pathologies within chest x-ray images, where we also have healthy chest x-rays. In the workshop, I will be ustilizing [<strong>Google Colab</strong>](https://colab.research.google.com/notebooks/welcome.ipynb) equipped with Python, TensorFlow, Keras, and GPUs to first develpo the pipeline, and then train, validate, and test the contructed models. Using Google Colab, you don't need to install any software/library packages, and as you know better than me, everything is just ready to use. Thanks much, Google! 

I would strongly recommend you to go through the [<strong>Google Colab</strong>](https://colab.research.google.com/notebooks/welcome.ipynb), but in case you would like to do the hands-on-practice on your local machine, there exists an instruction too. 

### Do you want to do the hands-on-practice using Google Colab?
If you are going to take advantages of Google Colab, and try to use this amzing collaborative environment for the proposed hands-on-practice, please follow the below steps, respectively. All we need is an stable internet connection and a browser! 


1) <strong> Dataset </strong>: Please [download](https://drive.google.com/file/d/13EPcGIn6ovvU0O4rCku3w5CFRi9CwQ1w/view?usp=sharing) the dataset. The present dataset is available as a single .ZIP file, which is basically a small subset of a large-scale dataset, the [chest x-ray image dataset provided by NIH](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community). The original paper of the dataset is available [here](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf). I thank NIH and the paper authors to privide an indeed interesting dataset to the research community. <strong>Note: Do not unzip the file, please!</strong> You will be asked to upload the current .ZIP file at your <strong>Google Drive</strong>.  

2) Within your <strong>Google Drive</strong>, please make a folder namely "<strong>chestimage</strong>". Upload the .ZIP file of the dataset, the "training_validation_2000.zip" file under the "<strong>chestimage</strong>" directory within your <strong>Google Drive</strong>.

3) <strong>Sample code/Implementation</strong>:
The sample code would be available [here](https://drive.google.com/file/d/13EPcGIn6ovvU0O4rCku3w5CFRi9CwQ1w/view?usp=sharing), during the workshop day. You don't need to make a copy of the code for now. That being said, using the current link, the entire implementation and sample codes would be available within your Google Colab environment. Please wait until we get together at the workshop. We, together, will go over the code, step by step. There is need to configure the Google Colab Runtime, so we can spped up the deep learning process with the use of GPUs. We will set iy up, together at the workshop. Again, please wait until we get together at the workshop. 

### Do you want to do the hands-on-practice at your local machine?

If so, please follow:

1) Download and install [Anaconda; Python 3.7 version](https://www.anaconda.com/distribution/#download-section). 
2) Go to the Anaconda Prompt. And make a virtual environemnt equipped with essential libraries. The command would be as follow:
    conda create -n DLFA2019 python=3.6 numpy scipy matplotlib spyder ipython jupyter pandas seaborn scikit-learn tensorflow-gpu keras
    
    
