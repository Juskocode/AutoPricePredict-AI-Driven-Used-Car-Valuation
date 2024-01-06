# AutoPricePredict-AI-Driven-Used-Car-Valuation
AutoPricePredict uses AI to forecast used car values accurately by analyzing various specs. Empowering buyers and sellers with reliable price estimations enhances market transparency and efficiency.

## Project Description: Used Car Price Prediction using Random Forest Algorithm

### Objective
Develop a Machine Learning model supported by the Random Forest algorithm to predict the prices of used cars based on their characteristics. The goal is to create a tool that assists in decision-making when searching for a used car. The provided dataset for model induction contains information about various used cars, including registration year, mileage, vehicle type, brand, engine power, fuel type, among others. Additionally, the objective is to identify the features that most significantly influence the vehicle prices.

### Development Tools
The Machine Learning model should be developed using Scikit-Learn and other supporting Python packages.

### Dataset Information
Two files, `dataset.csv` and `just_features.csv`, are provided for model induction and validation:
- `dataset.csv`: Contains 25,000 instances, each with the characteristics of a used vehicle, including the selling price.
- `just_features.csv`: Consists of 22,222 instances without the price indication.

### Output file
The outputfile `precos_estimados.csv` as only the columns 'id' and 'preco' in the following format:
|   id   |  preco   |
|-------|----------|
| 23346 |  1520.2  |
| 12344 | 10345.3  |
| 12112 |  5034.5  |