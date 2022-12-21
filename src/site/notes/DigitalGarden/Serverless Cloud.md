---
{"dg-publish":true,"permalink":"/digital-garden/serverless-cloud/"}
---

## Serverless.com Cloud

```ad-warning
15/11/2022 : This serverless seems experimental and may not be 100% working.
```

I've requested access to Serverless.com's Cloud service and so far, it seems to allow Javascript Frameworks only. I guess if I could pair up [Quasar](https://www.quasar.dev) Framework and build a SSR + PWA combo, I might be able to use serverless cloud but I am not entirely sure how their data(base) works yet. At a glance, it looks like a JSON flatfile feature. I will continue experimenting it when I get the free time.

ChatGPT says when it comes to building an e-commerce site on a serverless architecture:

>To build an e-commerce site using a serverless architecture, you will need to use a combination of different cloud services. Here is a high-level overview of how you might approach building an e-commerce site using serverless technologies:
>1.  Use a static site generator (such as Gatsby or Hugo) to build the frontend of your e-commerce site. This will allow you to create a fast, scalable, and secure site that can be hosted on a content delivery network (CDN) such as Amazon CloudFront.
>2.  Use a cloud provider's storage service (such as Amazon S3 or Google Cloud Storage) to store your product images and other static assets. This will allow you to serve these assets from a globally distributed network of servers, improving the performance of your site.
>3.  Use a cloud provider's serverless computing service (such as AWS Lambda or Google Cloud Functions) to build the backend of your e-commerce site. This will allow you to run code in response to events (such as a user placing an order) without the need to provision or manage servers.
>4.  Use a cloud provider's database service (such as Amazon DynamoDB or Google Cloud Bigtable) to store and retrieve data for your e-commerce site. This will allow you to store and retrieve data at scale, without the need to manage your own database servers.
>5.  Use a cloud provider's messaging service (such as Amazon SQS or Google Cloud Pub/Sub) to queue and process tasks asynchronously. This will allow you to offload tasks such as sending confirmation emails or generating invoices to a separate process, improving the performance and reliability of your e-commerce site.
>
By using these types of services, you can build an e-commerce site that is scalable, highly available, and cost-effective.

I've figured out most of these technologies, except for the last one for messaging service. I know some of it, such as RabbitMQ or ZeroMQ to handle pub/sub.