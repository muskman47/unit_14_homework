> ## Which model has a lower loss?
- The RNN over closing prices is showing the lower loss at ~.01 where the model over the fng data is showing a loss around ~.09.
>
> ## Which model tracks the actual values better over time?
>The model using the closing prices tracks the actual values better over time evidenved by the graph and comparison of real vs. predicted prices. 

> ## Which window size works best for the model?
A window size of 1 works best for both the models over the fng data and closing data. This was determined through trial and error and using a window size of 1 minimized the loss.