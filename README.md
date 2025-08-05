# Stock_Alert_AI_Pipeline
Introductory Level to grasp knowledge of web-scrapping, extract, transform, and loading into cloud service. Further, the project may evolve into data analysis and sending alerts based on sentiment of the news covered on targetted stocks.

### Setup enviroment by installing required packages
1. Open a vscode or anaconda terminal
2. The text file `requirements.txt` includes the required packages to start running the scripts
3. Setup an environment. Most populuar `python`. You can also use other py open source package: `poetry`
    a. Setup an environment:
        i. `python3 -m venv .env`
    b. Activate the environment:
        i. `source .env/Scripts/activate`
    c. Install the required packages:
        i. `pip install -r requirements.txt`
4. While running jupyter notebooks, we need to change `Kernel` to select the new `py environment`. By default, the system selects the default py environment. Change it from `Select Kernel`


### Data Architecture Diagram (POC)
[data_flow_diagram](https://github.com/sagarlimbu0/Stock_Alert_AI_Pipeline/blob/main/docs/stock_Alertai_Flow.png)
