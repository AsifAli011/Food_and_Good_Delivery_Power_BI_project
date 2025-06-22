# Food_and_Good_Delivery_Power_BI_project

## About Dataset

### Food and Goods Deliveries in Brazil


### What is the Delivery Center?
With its various operational hubs spread across Brazil, the Delivery Center is a platform that integrates retailers and marketplaces, creating a healthy ecosystem for sales of goods (products) and food (food) in Brazilian retail.

We currently have a registry (catalog + menu) with more than 900 thousand items, thousands of orders and deliveries are processed daily with a network of thousands of partner stores and delivery people spread across all regions of the country.

All of this generates data and more data all the time!

In view of this, our business is increasingly data driven, that is, using data to make decisions and looking to the future, we know that using data intelligently can be our great differentiator in the market.

This is our context and with it we propose a challenge in which you can apply your technical knowledge to solve everyday problems of a data team.

# Description of datasets

* orders: This dataset contains information about sales processed through the Delivery Center platform.
* deliveries: This dataset contains information about deliveries made by our partner delivery people.
* payments: This dataset contains information about payments made to the Delivery Center.
* drivers: This dataset contains information about our delivery partners. They work in our hubs and every time an order is processed, they make the deliveries to the consumers' homes.
* hubs: This dataset contains information about the Delivery Center hubs. Understand that Hubs are the distribution centers for orders and that is where deliveries are made.
* stores: This dataset contains information about store owners. They use the Delivery Center Platform to sell their items (goods and/or food) on marketplaces.
* channels: This dataset contains information about the sales channels (marketplaces) where our retailers' goods and food are sold.

  # Star Scheme and Model View:
  To define and manage relationships between tables in data model.
  Actually I create a model view according to Star Scheme.
  * Star Scheme: A data modeling design used in data warehouses and BI tools like Power BI, where data is organized to simplify and speed up reporting and analysis.
    ** Structue:
                * A central fact table (Order Table)
                * Connected to multiple dimension tables via one-to-many relationship (Payment, Deliveries, Hubs, Store, Drivers and Channel Tables)

  * Star Scheme Diagram:
    
    ![star](https://github.com/user-attachments/assets/d4a14bfd-460e-47a6-8561-6c2fe0b5b704)


   * Model View Diagram

  ![food](https://github.com/user-attachments/assets/75de4ef2-ebb6-49f4-9789-281d46a71514)


# Objectives:  

The main object of this project is to analyise data on the following way:

* To analyse Total Order and their Revenue & Delivery Cost and also Total Order and their Revenue in Month
* To analyse Total payment order with revenue with fee and Revenue with respect to payment method and payment status
* To analyse data of Hub Cities with respect to count of store name their orders and store segment, analyse the percentage plane price according to store segment and hub cities. Also analyse that plane plane price verus hub cities  and store segment. the last one is to analyse plane price verus hub name and store segment.
* To analyse the percentage of Driveres according to driver type and delivery status, Aslo analyse total order by driver type and deliveries by their deliveries status.


  ## To analyse Total Order and their Revenue & Delivery Cost and also Total Order and their Revenue in Month

* Dashboard
  
  ![food1](https://github.com/user-attachments/assets/1915ec12-bcdc-4b9d-a747-9176d0f101d7)

  ### Conclusion: 
As per line graph of total order in month, March, July and Oct having high order , while April and Aug have low Oder , with respect to that March, July and October have high Revenue as per bar chart , its mean that with the increase the order , revenue will also be increased.

## To analyse Total payment order with revenue with fee and Revenue with respect to payment method and payment status.

* Dashboard:
  
![food2](https://github.com/user-attachments/assets/4a8476dd-04f9-4352-a03f-7f0506c8ba26)

### Conclusion:

 * As  a lot of customers gives high preference to Store Direct Payment , while  Voucher OL(online) having low preference because of,  I think not having internet data to pay online. 
 * As per bar graph of revenue vs payment status, 98% customer Paid their payment, so it is good sigh for company, and also company should see , why the other 2% customer charge back and awaiting.

### To analyse data of Hub Cities with respect to count of store name their orders and store segment, analyse the percentage plane price according to store segment and hub cities. Also analyse that plane plane price verus hub cities  and store segment. the last one is to analyse plane price verus hub name and store segment.

Dashboard:

![food3](https://github.com/user-attachments/assets/e45c1aa3-f16d-4043-868d-3ffca30e623e)



### To analyse the percentage of Driveres according to driver type and delivery status, Aslo analyse total order by driver type and deliveries by their deliveries status.

Dashboard: 

![food4](https://github.com/user-attachments/assets/69bc399b-7d49-42c5-b851-a7b9cd865308)






  


  

