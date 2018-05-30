# Problem Statement:
One of the critical need for SaaS application is connecting it to a billing system.

There are 4 critical events as part of the SaaS Billing. They are 
  * Onboarding access to new Customers or Subscription
  * Free Trials
  * Upgrades
  * Cancellations
  * Re-Subscription

The challenge is handling these events multitude of SaaS applications within an organization, such as restricting access to an application when a trial expires 
or if there no longer has a valid funding source attached to an account etc.

The Purpose of this system is to provide a unique, simple and effective solution for the most used functionalities associated with billing

## 3rd-party vs in-house billing

There are many SaaS businesses out there with custom-built in-house billing systems driving their back end. Items to consider

In-house billing systems:

    * Require a lot of complex logic to handle payment transactions 
    * May require a legal presence in each country in which you wish to do 	business
    * Will require a large ongoing investment in security.  Billing system will need to stay at the forefront of the latest payment tech
    * Maintain a great level of control over the entire management and processing of payments (and the data associated ) within the  platform
    * Still need to interact with 3rd-party systems along the way, for card authorization, etc.

3rd-party billing systems:

    * Handle nearly all of the complex logic associated with payments
    * Take care of the legal side of handling transactions in multiple countries
    * Usually, maintain the highest possible level of security
    * Support a number of one-click integrations with other platforms (analytics, accounting etc.)
    * Allow reasonable flexibility and control when it comes to customisation
    * Deliver a consistent payment experience for the end user
    * Usually take a small transaction-based fee, rather than the large upfront cost of building your own

The advantage of having a working system up and running in a matter of hours will almost always win against giving away a small slice of each transaction’s revenue.

## High level Requirements

   * Handle both subscription and one-time charges (such as setup costs, fees etc.)
   * SaaS Billing - 3 Parts    
   
      * Subscription Mgmt Platform 
      * Payment Gateway
      * Merchant Account 
      
   * Subscription tiers, discounts and coupons (example, Chargebee, Recurly and Chargify )
   * Analytics T o understand customer churn, retention and optimize your MRR, ARR etc ( Baremetrics, ChartMogul, SaaSOptics)
   * Mobile Support
   * Invoicing & Tax Handling 
   * Handling Card Failure 

Billing Simplified Model: 
![alt text][billing-simplified]

[billing-simplified]:  https://github.com/rajasoun/subscription-management/blob/master/Billing-Simplified.jpg
