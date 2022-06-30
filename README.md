# Prediction of Invioce Payment Date

This is an Emoji and Text Recognizer made for Cassandra, Udyam'22, organized by IIT(BHU).</br>

## Problem Statement <br/>
Our Sponsors are looking out for skillful Data Scientists who can apply Machine Learning to predict the cash flow of their clients or in simple words they ask you to forecast when the payment of an invoice will occur after the company receives the payable invoice. Ultimately, the task is to build a model that helps estimating when an invoice will be paid. The estimation doesn't have to be an exact date and time, a rough estimation in terms of days is sufficient for this task. You need to predict the Number of Days until Payment using the Dataset provided to you.<br/>

Our Goal is to predict Number of Days until Payment feature by training a Machine Learning model on the Train Data.<br>

## Dataset Discussion <br/>
There are various Columns in Dataset such as:-
- **Description** : The textual description entered by the user during recording the invoice on the accounting system (string).
- **Vendor Name** : The name of the vendor/supplier who provided the goods or services (string).
- **Created** : The date and time of entering the invoice details on the accounting system (datetime).
- **Invoice Date** : The date and time of the invoice. It represents when the goods or services have been delivered to Traxes (datetime).
- **Due Date** : The date and time when the invoice is due to be paid by Traxes (datetime).
- **Amount** : The cost of the goods/service provided by vendors and due to be paid by Traxes (float).
- **Settled** : The amount that has been paid by Traxes to vendors on the payment date (float).
- **Outstanding** : The unpaid part of the invoice in which Traxes is required to pay (float)
- **Number of Days until Payment** : count of days after Invoice Date after which payment was made.
