# Dukaan_ihack_submission

**Name** - Bhuvan Aggarwal
**Institute** - IIT Bombay
**Roll No.** - 190040026

**Solution Topic** - Demand Forecasting for retailers

**Problem background** - The shortage or surplus of inventory is a common problem faced by almost all the dukaandars of India and this problem even aggravated during the time of covid. Both surplus and shortage of inventory leads to huge losses for the retailers. This issue can be resolved if they can predict the future demand for the products depending on the seasonality and the changing market. So, here comes the AI technology to help them in this.

**Data** - As I didn't have the access to real data form the dukaandars therefore I chose to go forward with a dataset from kaggle which can be found <a href='https://www.kaggle.com/felixzhao/productdemandforecasting'>here.</a> The data contains product demands from various warehouses and for various product categories.

**Solution** - Currently, I have merged the product categories and predicted the daily demand for one warehouse to better demonstrate the working. I have used the sarimax model for the forecasting. This model is highly generalised can be easily extended to each product category or product id and any type of dukaandar. It will help the dukaandars to manage their orders and inventory in a more effecient and productive manner. 

**Future Work** - All the following things are the ones which I wanted to include in the solution but couldn't due to the time constraint.  
- Make a more accessible UI for the dukaandars. 
- Try other models like Prophet and LSTMs
- Use online learning so non tech people can use it as a black box system which is always updated
- Incorporate news and market trend data in addition to the demand history data to make the model more robust.
