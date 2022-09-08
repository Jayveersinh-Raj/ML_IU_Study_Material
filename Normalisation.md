**Feature Scaling:** We need it to get all the features in the same range. However, if they are closer to each other there is no need to scale it. We generally use
`Normalisation` for it. `Gradient Descent` works better and faster if they are in close range or scaled. *If in doubt, scale it, there is no harm to that*.

<img width="657" alt="image" src="https://user-images.githubusercontent.com/69463767/189214215-bbae4790-c655-4ed4-b890-1b0acb512bb9.png">


Normalisation is used to get all of our features in the same range (-1 to 1). However, there are 2 ways to achieve it :
1. Mean Normalisation
2. Z-Score or Standardisation.

**NOTE :** `Z-Score or Standardisation` is better than `Mean Normalisation` because the former considers entire dataset, and converts it to normal while the later just 
considers the max and min value, hence, the later does not work good with data that are more prone to outliers.

Mean normalisation:

<img width="703" alt="image" src="https://user-images.githubusercontent.com/69463767/189201360-87d08ada-19e3-4564-bebe-a6a9638bf254.png">

Z-Score or Standardisation :

<img width="692" alt="image" src="https://user-images.githubusercontent.com/69463767/189213522-6cfbbd78-b546-42e5-92a8-656b34ace2f6.png">

