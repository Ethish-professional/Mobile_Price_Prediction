# Mobile Price Range Prediction

This project aims to predict the price range of mobile phones based on their specifications. The prediction is made using various features such as battery power, 3G capability, WiFi, Bluetooth, RAM, etc.

## Dataset

The dataset used for this project contains the following columns:

- id: ID
- battery_power: Total energy a battery can store in one time measured in mAh
- blue: Has Bluetooth or not
- clock_speed: Speed at which the microprocessor executes instructions
- dual_sim: Has dual SIM support or not
- fc: Front Camera mega pixels
- four_g: Has 4G or not
- int_memory: Internal Memory in Gigabytes
- m_dep: Mobile Depth in cm
- mobile_wt: Weight of the mobile phone
- n_cores: Number of cores of the processor
- pc: Primary Camera mega pixels
- px_height: Pixel Resolution Height
- px_width: Pixel Resolution Width
- ram: Random Access Memory in Megabytes
- sc_h: Screen Height of the mobile in cm
- sc_w: Screen Width of the mobile in cm
- talk_time: Longest time that a single battery charge will last when you are
- three_g: Has 3G or not
- touch_screen: Has a touch screen or not
- wifi: Has WiFi or not

## Objective

The main objective of this project is to help companies estimate the price of mobile phones accurately, enabling them to provide tough competition to other mobile manufacturers. Additionally, it serves as a useful tool for consumers to verify that they are paying the best price for a mobile phone.

## How to Use

To use this project, follow these steps:

1. Ensure that you have the required dependencies installed. You can find them in the `requirements.txt` file.
2. Prepare your dataset in a CSV format similar to the provided dataset.
3. Adjust the data preprocessing and feature engineering steps as per your requirements.
4. Train the machine learning model using the provided notebook or script.
5. Evaluate the model's performance and tune hyperparameters if necessary.
6. Use the trained model to predict the price range of new mobile phones based on their specifications.

Feel free to explore the code, modify it, and adapt it to suit your specific needs.


