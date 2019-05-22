# Billing system based on product image segmentation
This is a repository for a project based on machine learning for billing system.

Objective:Real time object detection-based billing system (minimal human intervention billing and analysis system based on real time object detection)

*Result sample of product inference:*
<img src="https://raw.githubusercontent.com/thewitking/billing-system/master/etc/images/sample_output.png" title="Result sample" alt="sample output">


As per shown result we can see that our inference model trained on retinanet model works absolutely fine and provides us the list of products segmented in the image (such image could be the result of camera capture input when customer place all the purchased items in a tray or relevant place)

**Ouptut Bill Amount**


<img src="https://raw.githubusercontent.com/thewitking/billing-system/master/etc/images/output_total.png" title="Result sample" align="center" alt="sample output">



**Description**

*Products in Image dataset*

>Consider that a store has 6 different products as shown below.

<img src="https://raw.githubusercontent.com/thewitking/billing-system/master/etc/images/product.png" title="Result sample" align="center" alt="products">

Team: 
MANISH SONI (ms11313); 
Karthik  (ks5189)


Project description: 
The project we implemented is Real time object detection based billing system. We wanted to build a solution around object detection and evaluating its price, and analysis of sell for inventory management (can be extended).


Idea: idea is to use a deep neural network approach for various object detection so to evaluate price of all the items. And to use regression analysis for predicting the inventory suggestions.



Future- Extension: This project can be extended with a sophisticated network of high resolution cameras to evaluate the price of objects as soon the customer picks or drops a product item from certain area. Which makes the whole shopping experience for the customer smooth. While in parallel the same system can recognize the different customers and help them with their shopping experience.


