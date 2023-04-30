# Problem:

1) Describe the problem:
Climate change - leads to severe droughts, and extreme weather eventss that can damage crops and reduce yields

2) water scarcity, South african farmers struggle with access to enough water to irrigate their crops
Good motivation for why we need better water management: https://www.wits.ac.za/gci/gci-news/news-archive/7-impacts-of-climate-change-on-south-african-agriculture/

3) Pests and diseases i.e. locusts, armyworms, citrus greening disease ( https://repository.up.ac.za/handle/2263/15886 ).

=====================================
### Who benefits from this?
small-scale farmers in developing communities. They have limited resources, more vulnerable to the effects of climate change, soil degradation


We want to prioritse soil health, water conservation, natural pest management  while increasing productivity and reducing the environmental impact

That way with increased crop yield they can access new markets, increase profits.



### current solution in south africa:
- access to finance: land bank and CASP these provide loand.

- Access to markets: department of agriculture market access programme
- training and skills from Agricultural Research Council's Farmer Support and Development Programme


### by using machine learning
1) improved decision making - when to plant, irrigate, harvest crops based on real time weather data, soil moisture

2) early warning systems: predict disease and outbreak before they occur (reduce pesitcide use)

3) usingh satellite imagery to create detailed farmland maps identifying areas of soil variability, precisely make changes to improve soil quality and resource use.

### why is there an opportunity?
Consumers are becoming more aware of the products they pay and will be interested in purchasing food from sustainable sources that are environmentally friendly and socially responsible practices, while paying premium for it. 


========================================

# Point 3
- where to collect data and labels? how to do it cost effectively and reliably?


- what considerations in regards formatting and processing?


- what kind of ML is this?

- what methodology?
    - using decision trees: when to plant harvest and irrigate based on real time data on weather, soil moisture... predict likelihood of pest and disease outbreak

    - naive bayes+ log regression:  analyze historical data of crop yields and environmental factors to identify patterns and make predicitons of future yields. 

    - linear regression: create models to predict crop yields 

This all depends on the type of data we have available.
- Overfitting/ underfitting:

data from small scale farmers will be noisy(overfitting)/limited and the relationshipps between the features may be difficult to capture.

Underfitting if model is too simple and can't capture the underlying trends in data

We will need to perform regularisation techniques, validate models on independent test data, collect more data to capture the underlying relationships between features and crop yield.

- validation of model

We can use coefficient of determination  ($R^2$) measure the proportion of variation in the target yield  A higher $R^2$ better model, lower not capturing pattersn in the data

use Root mean squared error.


Best way is to obtain feedback from small scale farmers to ensure that the model is meeting their individual needs, and providing practical applications for improving famring practices.

### Partner with:

Agricultural organizations
South African Agricultural Union or the National African Farmers' Union

Technology companies

Non-profit organizations - African Agricultural Technology Foundation or the Small Enterprise Foundation 

Government agencies

private corporations 


### profit through subscription
consulting services
data licensing
partnerships with agribusinesses