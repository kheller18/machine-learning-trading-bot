# Machine Learning Trading Bot

![license badge](https://shields.io/badge/license-mit-blue)


## Description

This project uses different machine learning models to try and create a trading algorithm that predicts early signals for entry / exit strategies. The basis of this algorithm uses Simple Moving Average (SMA).

The three different models created are described below:
  1. Baseline Model with the following paremeters:
    + 4-day fast SMA
    + 100-day long SMA

    ![baseline](/Images/baseline.png)

  2. Tuned model (hyperparemter)
    + 4-day fast SMA
    + 140-day long SMA

    ![tuned](/Images/tuned.png)


  3. KNN (K Nearest Neighbors) model with baseline paremters
    + 4-day fast SMA
    + 100-day long SMA

    ![knn](/Images/knn.png)

## Table of Contents

- [Machine Learning Trading Bot](#machine-learning-trading-bot)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [1. Installation](#1-installation)
  - [2. Usage](#2-usage)
  - [3. License](#3-license)
  - [4. Contributing](#4-contributing)
  - [5. Tests](#5-tests)
  - [6. Deployment](#6-deployment)
  - [7. Contact](#7-contact)


## 1. Installation

  If you would like to clone the repository, type "git clone https://github.com/kheller18/machine-learning-trading-bot.git".
  In the terminal, with the conda dev environment activated, install the following packages and dependencies before running the crime analysis application. To understand how to install these, refer to the [Usage](#2-usage)

  * [csv](https://docs.python.org/3/library/csv.html) - Used to store data

  * [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) - *version 3.4.4* - Used to create and share documents that contain live code, equations, visualizations and narrative text.

  * [pandas](https://pandas.pydata.org/docs/) - For data analysis.

  * [pathlib](https://docs.python.org/3/library/pathlib.html) - *version 1.0.1* - This was used to locate through the directory or file path.

  * [scikit-learn](https://scikit-learn.org/stable/) - *version 1.2* - Tools for data analysis

  * [imbalanced-learn](https://imbalanced-learn.org/stable/) - *version 0.10.1* - Tools for data analysis

  * [NumPy](https://numpy.org/) - *version 1.24.0*- Provides tools when dealing with classification with imbalanced classes

  * [TensorFlow](https://www.tensorflow.org/) -*version 2.0.0*- Deep neural network creation

  * [Keras](https://keras.io/) -*version 2.9.0*- Deep neural network creation


## 2. Usage

  After cloning the repository locally, you'll need to have the packages listed in [Installation](#1-installation) installed on your machine. To do so, you'll need to activate your conda dev environment and running the following commands:

      ```
      pip install pandas
      pip install hvplot
      pip install jupyterlab
      pip install scikit-learn
      pip install imbalanced-learn
      pip install numpy
      pip install tensorflow
      pip install keras

      ```

  After all of these are installed, please refer to the [Deployment](#6-deployment) section for instructions on how to view or edit the notebook.


## 3. License

	MIT License

  Copyright (c) 2023 Keenan Heller

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in all
  copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  SOFTWARE.


## 4. Contributing

  + [Keenan Heller](https://github.com/kheller18)


## 5. Tests

  + There are currently no tests associated with this project.


## 6. Deployment

  + There is currently no live deployment of this notebook on a common server, but the user has the ability to run this notebook locally on their machine via:
    + `Jupyter Lab`: Navigate to root of the directory and type "jupyter lab machine_learning_trading_bot.ipynb".


## 7. Contact

  + [Keenan's LinkedIn](https://www.linkedin.com/in/keenanheller/)
