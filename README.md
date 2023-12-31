# Customer-churn-using-ANN

Dataset: https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction

## What is Customer Churn?

According to Shewta at [HubSpot](https://blog.hubspot.com/service/what-is-customer-churn), Customer churn is one of the most important metrics for a growing business to evaluate. This number can give any company the hard truth about its customer retention.

It means that customer churn prediction is a process used by businesses to predict which customers are at risk of ending their relationship with the company or the company's product.

![](customer-churn.jpg)

img source: https://www.forbes.com/sites/allbusiness/2017/09/05/the-4-keys-to-boosting-your-customer-retention/?sh=393a6c925640

My goal was to identify which customer is likely to churn, on an old dataset from which we can get some meaningful insights and in turn forecast which customer might leave the bank or that service. By predicting churn, companies can practice customer retention strategies, to decrease the chance of the customer leaving them.

Customer churn strategies are commonly employed in various industries, including banks, e-commerce, subscription-based services, etc, where customer retention is crucial for maintaining profits and growth.

For my customer churn prediction model, I used **Artificial Neural Network** machine learning algorithm.

## Artificial Neural Networks

Artificial neural networks, or ANNs, are a subset of machine learning and are at the heart of deep learning algorithms. This computational mode is inspired by the structure and functioning of the human brain's neural networks. The building block of ANNs is a neuron or node. These neurons are interconnected in layers, consisting of an input layer, one or more hidden layers, and an output layer as shown below. Each neuron receives input data, processes it, and produces an output, which is passed on to the next layer. The training of this network involves, presenting the data to the neurons and their corresponding output labels. The model then adjusts its parameters, including weights and biases, through a process called backpropagation, which aims to minimize the difference between its predicted output and the actual output. This process allows to train the networks to learn complex patterns and relations within the dataset. Once trained, ANNs can be used to make predictions on new, unseen data with great success.

![](neural-network.jpg)

img source: https://www.geeksforgeeks.org/artificial-neural-networks-and-its-applications/

## Result

- Developed a customer churn prediction model, using Python and machine learning, and implement a 3-layered Artificial neural network.
- Conducted EDA and data visualization, to produce key findings.
- Successfully achieved an accuracy of ~86%.

## Conclusions

- The proportion of people staying and exiting was the highest for the people of Germany.
- Younger people tend to stay than middle-aged people.


## Customer retention strategies

Now the question arises, how do we retain customers? According to [Forbes](https://www.forbes.com/sites/allbusiness/2017/09/05/the-4-keys-to-boosting-your-customer-retention/?sh=393a6c925640), the best methods are :

- **Know your customers better than they know themselves**
  
  Customer satisfaction and ratings plummet when they feel that they are being ignored. A good strategy would be to take some time to create relationships with the customers and get to know them, and their needs. This could go a long way.
  
- **Implement feedback systems**

  A good strategy for customer retention is to allow them to speak for themselves. Short but precise surveys or feedback from their loyal customer will help you know how they feel about the company or the product. Rewarding them after feedback can prove to them that you value their time and comments.
  
- **Go beyond nice and polite**

  There's an old saying: *It's never crowded on the extra mile.* Go beyond the services that are provided and offer a gift as an unexpected surprise. This random act of kindness will leave a lasting impression. Even a small freebie for their birthday can be a good strategy.

