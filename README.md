# Investment Banking & Asset Manager

The following project contains several templates:

- Asset
- Portfolio
- Order
- Trade
- Investment

## Description of the project

The main idea of this project is to replicate some tasks in the asset management world by a financial services company using real-world scenarios such as creating assets, orders, portfolios, manage investments, and even replicate a potential trading.

These types of companies run into some heavy rules and criteria to increase their portfolio value white carefully mitigate some risks.

What I've in mind is to create a Smart Contract app using DAML to reproduce those steps in an automated way.

### How to run the project

Down below are the scripts associated with each operation you can fulfill, when you click the Scripts result you would be able to see the chain for each test.

- Create asset
- Create a portfolio
- Place an order to simulate buying and selling stocks
- Create an investment
- Execute a trade

How to run it with a UI.

1. Sign up and create a new project in the web page: https://hub.daml.com/
2. Go to the daml.yaml file and point the scenario to the daml file you created
3. Create a DAR file, executing the following command

```
daml build
```

4. Upload your DAR file into the project created. There you can use the UI to create the parties and test it out.

### License

By Christian Retana.
