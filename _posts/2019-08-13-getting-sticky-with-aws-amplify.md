---
date: '2019-08-13 16:27 -0400'
published: true
title: Getting sticky with AWS Amplify
featured_image: /images/amplify-lander.png
description: Getting sticky with AWS Amplify
---
## Sticky Tech Debt

![aws amplify]({{site.baseurl}}/images/going-serverless-aws-amplify.jpeg)

AWS Amplify is a CLI tool and a set of libraries, it’s been a good way to get used to AWS services and has decreased my time to launch on a recent MVP. However, **I can’t help but feel that Amplify (or at least the way I’ve implemented it) is a little too sticky.**

The logic of how I retrieve s3 cloud signed URL’s using dynamo DB and graphql is tightly coupled with my react-app front end, but by having awareness of a problem I do feel slightly better about the situation.

> All too often I’ll over-optimize from the start leading to shipping jack sh*t, this feels much better.

I’ve rationalized it as taking on tech debt, filed away in my head as a problem for the future me. Debt doesn’t always have to be bad right? I’ve made the downpayment and I’ll start paying for it, all the while living in my fancy serverless home. All too often I’ll over-optimize from the start leading to shipping jack sh*t, this feels much better.

My plan is to make a few utils that implement the AWS calls, then at least I’ll feel some sort of control through centralizing my concerns.

So, for now, I’m living with the debt. If it becomes a problem then it means the idea itself is doing well. 

