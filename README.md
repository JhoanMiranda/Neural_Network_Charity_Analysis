# Neural_Network_Charity_Analysis



The analysis was made to create a neural network model that guides us where to invest.
Using Jupyter Notebook and a supervised machine learning (neural networks) we trained the load data. Then we optimized the data to remove the noisy variables, using more neurons in the hidden layers, adding more hidden layers, and using different activation functions, lastly we use check points to save our progress 


## Conclusion

After the analysis was made, we were able to answer the following questions. 


•	What variable(s) are considered the target(s) for your model?

        o	Was IS_SUCCESSFUL

•	What variable(s) are considered to be the features for your model?

        o	APPLICATION_TYPE

        o	AFFILIATION

        o	CLASSIFICATION

        o	USE_CASE

        o	ORGANIZATION

        o	STATUS

        o	INCOME_AMT

        o	SPECIAL_CONSIDERATIONS

        o	ASK_AMT

•	What variable(s) are neither targets nor features, and should be removed from the input data?

        o	EIN

        o	NAME

•	Compiling, Training, and Evaluating the Model

        o	How many neurons, layers, and activation functions did you select for your neural network model, and why? I use a total of:

First attempt Neurons = 80, Hidden Layers = 30 Activation used was sigmoid

![Screenshot (158)](https://user-images.githubusercontent.com/114957364/223308400-fb98d293-a3c8-4511-8835-81fb5b3dcf2e.png)

Optimization Code: Neurons = 100, Hidden Layers = 60, Hidden Layers = 30, Hidden Layers = 10, Activation used was linear

![Screenshot (157)](https://user-images.githubusercontent.com/114957364/223308551-021539a2-57ef-42f3-952d-711e992f045a.png)

Test #1 Neurons: 50, Hidden Layers = 20, Hidden Layers = 15, Activation used was sigmoid

![Screenshot (156)](https://user-images.githubusercontent.com/114957364/223308659-2026debf-bcd5-466f-aeb5-4da91bfec8a1.png)

Test #2: Neurons: 70, Hidden Layers = 40, Hidden Layers = 20, Hidden Layers = 10, Activation used was linear

![Screenshot (155)](https://user-images.githubusercontent.com/114957364/223308761-4c13afdd-15c8-46a9-aad8-7c089b00928d.png)

