################### Machine Learning for InfoSEC ###################################

The scripts will help us with our security investigations.
We are using machine learning algorithms with python to predict and train our model to become more resistance to attacks:

        Malware detection with API Calls, PE Headers, and Deep Learning.
        Bots, Advanced Persistent Threats & Anomaly detection with ML and ELK. 

Let's build up our machine where our code will run.

##### Installation steps:

1. Download and install virtualbox: https://www.virtualbox.org/wiki/Downloads  
2. Download and install kali_64-bit: https://www.kali.org/downloads/  64-bit. 

( apt install python-pip python-dev python-virtualenv )     

3. Install and Create a Virtual Environment inside the vm: Kali# mkdir mlfs_project
        Kali# virtualenv --system-site-packages mlfs_project
        kali# cd mlfs_project 
        kali~/mlfs_project# source ~/bin/activate
         
4. kali~/mlfs_project/mlfs_project# pip install keras 
5. kali~/mlfs_project/mlfs_project# pip install pandas
6. kali~/mlfs_project/mlfs_project# pip install matplotlib
7. kali~/mlfs_project/mlfs_project# pip install -U scikit-learn
8. kali~/mlfs_project/mlfs_project# pip install -U nltk
        >>> nltk.download()
                install all packages
                
                
9. kali~/mlfs_project/mlfs_project# pip install Theano 
10. Install anaconda. https://docs.anaconda.com/anaconda/install/

