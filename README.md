# Strategic Customer Segmentation and Demand Prediction

The aim of this study was to segment customers and predict demand by analyzing historical pricing data. 
This segmentation is based on purchasing behaviors and the revenue they help the company generate. 
Complementing this, we predicted the daily and weekly demand which is in terms of the sales of different products using an XGBoost regression model.

__Segmentation__

![image](https://github.com/kumarsauravjha/Customer_segmentation_demand_prediction/assets/143224932/d6ea7ca5-a769-48a5-b2c1-afcd57099393)

Fig. Comparison of results of k-means and Hierarchical clustering techniques for customer segmentation


![image](https://github.com/kumarsauravjha/Customer_segmentation_demand_prediction/assets/143224932/031c4714-b5ea-4fe3-b141-30c467360ea4)

Fig. Final customer segments (right) from k-means clustering.


![DATS_6103_Project_Group-2 pptx](https://github.com/kumarsauravjha/Customer_segmentation_demand_prediction/assets/143224932/157f8114-0d0d-4d59-90af-15ff7bb9a735)

Fig. Insights in terms of average parameters of the four customer segments identified from k-means clustering.


__Demand Prediction__

![image](https://github.com/kumarsauravjha/Customer_segmentation_demand_prediction/assets/143224932/763593f4-6b36-4cd6-bbcf-f483eb9eea3d)

Fig. Actual vs predicted daily demand (sales) for the four customer segments by XGBoost model. The dashed lines divide the 5 cross validation folds.

![image](https://github.com/kumarsauravjha/Customer_segmentation_demand_prediction/assets/143224932/0c8481b4-1700-4c51-8654-5eb0ae270928)

Fig. Actual vs predicted weekly demand (sales) for the four customer segments by XGBoost model. The dashed lines divide the 5 cross validation folds.




