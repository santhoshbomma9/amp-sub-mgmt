# Azure Marketplace SaaS Offer Integration Sample Application

## Simple Disclaimer
**This application is a sample only and must be treated that way. It is NOT a production level code. It is written for my personal use.**  

## SaaS Offer background
If you are here and wondering what this sample is all about, please continue to read otherwise feel free to skip and continue to the next section. The intended audience for this sample is a **Company(Independent Software Vendor/Publisher)** who ideally have or going to have a [SaaS](https://azure.microsoft.com/en-us/overview/what-is-saas/) and want to sell it to their customers. 
One of the cloud selling markets to sell a [SaaS](https://azure.microsoft.com/en-us/overview/what-is-saas/) is [Azure Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/) and you can use Azure Marketplace store front to sell your SaaS application to your customers. Find more information on [Azure Marketplace here](https://docs.microsoft.com/en-us/azure/marketplace/). When you are selling your SaaS on Azure Marketplace, Microsoft helps deal with the transactions. [Benefits of selling through Commercial Marketplace](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-publishers-guide#commercial-marketplace-benefits). 

To sell anything on Azure Marketplace you would need to create an offer in [Partner Center](http://partner.microsoft.com/)/[Partner Portal](http://cloudpartner.azure.com/) and publish to Azure marketplace. If you are not already on Azure Marketplace, [please find more information here](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/create-account) .

There are [many types of offers](https://docs.microsoft.com/en-us/azure/marketplace/publisher-guide-by-offer-type) you can create, publish and sell on Azure Marketplace and SaaS offering happens to be one of them. When you create different types of offers there are different requirements which needs to be fulfilled to successfully publish it to public.

As this sample is a requirement for creating a SaaS offer, we will only talk about SaaS offering but if you like you can view the information-about/requirements for different offerings [here](https://docs.microsoft.com/en-us/azure/marketplace/publisher-guide-by-offer-type). Please read more about [SaaS offer on Azure Marketplace here](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-saas-applications-technical-publishing-guide).

You would need to follow [SaaS offer checklist here](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/offer-creation-checklist) to create one. 

On a high level below are things we need to be addressed to publish and sell a SaaS offer.
1. Complete Tax profile and Payout (one-time activity, just in case if not already done so) 
2. Marketing and Plan/Pricing model (how you want to display your offer and how you want to price it)
3. Technical requirements (An application to interact between the subscriber/customer, company/publisher and Azure Marketplace - This is exactly what this sample is for)

#### Steps Explanation

1. Complete Tax profile and Payout 
This is a one-time activity, just in case if not already done so. Basically, how SaaS offer works is
- Put your offer in Azure Marketplace
- Customer buys the offer 
- Microsoft bills the customer as per the selected billing term by customer
- Microsoft pays out to the Company/ISV

## About the sample
