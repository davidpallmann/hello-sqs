# Hello, SQS!

This is the code project for the [Hello, SQS!](https://davidpallmann.hashnode.dev/hello-sqs) blog post. 

This episode: Amazon SQS. In this [Hello, Cloud](https://davidpallmann.hashnode.dev/series/hello-cloud) blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce Amazon SQS and use it in a "Hello, Cloud" .NET program. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, SQS Project

We’re going to create a queue in the AWS console and see how we can monitor it. Then, we'll create two .NET 6 console programs. One will simulate a storefront, using the AWS SDK for .NET to send queue messages (our message producer). The other will simulate an order fulfillment service, using the SDK to receive queue messages (our message consumer).

See the blog post for the tutorial to create this project and run it on AWS.

