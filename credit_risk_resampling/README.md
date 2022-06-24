# credit_risk_resampling
Module 12

**The application is published [here](https://github.com/avangelinac/credit_risk_resampling) as a github project page.**

---
## Installation 
<!-- This is an example of how to list things you need to use the software and how to install them. -->
A text editor such as [VS Code](https://code.visualstudio.com/) or [Sublime Text](https://www.sublimetext.com/)

## Install

1. Clone the repo
   ```sh
   git clone https://github.com/avangelinac/credit_risk_resampling.git
   ```

2. You don't need to install pip - Conda comes with pip and you can also use the command
    conda install 'package name'
   
3. Install Conda according to the instructions based on your operating system.
    For windows users you MUST use the Administrator PowerShell. Users with AMD Processors MUST use the Administrator PowerShell 7 (X64) version
  
    Once installed Conda has an Admin PowerShell version shortcut - look on your Start menu for it.
    This shortcut will prove very useful at times when you need to install other apps or make adjustments to your installation

    Once installed you will see (base) on your terminal
   
4. Activate Conda Dev environment
   ```sh
   conda activate dev
   ```
   You should now see (dev) on your terminal

5. Install JupyterLabs
   ```sh
   pip install jupyterlab
   ```

6. Run JupyterLabs
   ```sh
   jupyter lab
   ```
   A browser window should open on localhost:8888/lab

## Usage

* Machine Learning Model 1 `LogisticRegression`:
  * `balanced_accuracy_score` = 0.9520479254722232
  * `precision`  0=1.00,  1=0.85
  * `recall`     0=0.99,  1=0.91

* Machine Learning Model 2 `RandomOverSampler`:
  * `balanced_accuracy_score` = 0.9947308560359689
  * `precision`  0=0.99,  1=0.99
  * `recall`     0=0.99,  1=0.99

---
## Instructions

This challenge consists of the following subsections:

* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data 

- ### Part 1
![Split the Data into Training and Testing Sets](images/ex_one.png)
- ### Part 2
![Create a Logistic Regression Model with the Original Data](images/ex_two.png)
- ### Part 3
![Predict a Logistic Regression Model with Resampled Training Data](images/ex_three.png)
- ### Part 4
![Write a Credit Risk Analysis Report](images/ex_four.png)


---
## Contributor Commits Part 1-4
Commits by Avangelina Cazares Parts 1-4

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
## Disclaimer
Not financial advice

---
## License
Maybe MIT & Open Source