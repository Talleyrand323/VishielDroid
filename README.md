
# VishielDroid

Greetings, to those who have visited this repository 😎 <br/>
Here we provide some materials that might be helpful for your reviewing process as follows:

- **trained_SVM.onnx:**  a pre-trained model we put inside of Vishing Detector for our <br/> experiments on VishielDroid's system overhead (in section 5.7 of our paper). <br/>
- **test_cases.csv:**  475 benign, 230 Vishing cases each represented in the form of a feature <br/> vector extracted from the samples from 2023. VishielDroid uses 98 features in total <br/>
 -> 60 P_install features with the suffix '-ins' / 38 P_runtime features ending with '-run'. <br/>
- **test_code.ipynb:**  a code file where you could load from both the trained model and <br/>
the test cases and find out the detection result, just by pressing <code>Shift</code> and <code>Enter</code> <br/> a few times on your keyboard. <br/>    

The source code and custom OS image files will be released, later !


## How to use
  
1) Please download 3 files above into the same directory.
2) Open up your Jupyter Notebook (or a webpage for Google Colab).
3) Execute the code blocks of 'test_code.ipynb' one by one from the top.  


## Dataset

Due to both limited capacity of the repository and ethical issues, we provide the <br/>
hash values of the dataset from 2021 to 2023 that we used in our paper.<br/> 

In case of the malware samples (Vishing_202*.txt), you could use the hash values to <br/>
get the information from [VirusTotal](https://www.virustotal.com), and as for the benign samples (Benign_202*.txt), <br/>
you could refer to [AndroZoo](https://androzoo.uni.lu/api_doc) and download the according APK files.









