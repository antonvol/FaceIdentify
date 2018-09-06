# FaceIdentify
Ordinary system to identify person by face



# Requirements
Anaconda => Python3.5+ <br />
Jupyter Notebook (Conda set) <br />
Dlib ( http://dlib.net/ )


# Usage
//For this example i used pictures of my friend

Run the .ipynb file at jupyter notebook or copy to your <br />
At line 43 (file = 'Radick.jpg') change the directory and way to person you would like to check <br />
At line 97 (img = io.imread('C:\\Users\\Admin\\FRS\\Radick\\f2.jpg')) change the directory and way another picture of same person <br />
Basically Dlib says that result of eucledian distance should be less than 0.6, which means the person identifies correctly. I reccmmend to change it to 0.63(in my expirience)

# Example
Load first picture and found face descriptor: <br />
![alt text](https://pp.userapi.com/c845418/v845418130/e2cbe/7aJZdEnpHfI.jpg)

Load second picture and found face descriptor2: <br />
![alt text](https://pp.userapi.com/c845418/v845418130/e2cc5/ye9eW8Bp2kw.jpg)

See result: <br />
![alt text](https://pp.userapi.com/c845418/v845418130/e2ccd/TOArTnn5IAk.jpg)


