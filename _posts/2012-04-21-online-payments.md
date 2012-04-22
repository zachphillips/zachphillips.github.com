---
layout: post
title: Solving the Online Payment Problem
link: http://www.baekdal.com/insights/we-need-to-drastically-simplify-payments-online/
---

Thomas Baekdal:

> The solution is quite simple. The technology already exists, and it is easy to implement. We need to think of payments the same way as Facebook think (sp.) of the Like button.

I don't think the solution is this simple. It would be arguably a better user interface, but it presupposes that there is one good payment service we can all agree on.

PayPal already has something virtually equivalent to this, though it does take you away from the site temporarily. It's pretty quick, and like all other things PayPal, it's as ugly as road death. 

But all you have to do is enter your PayPal password, change the funding source if you want, and you're done. I love when I go to pay for something and they have a PayPal checkout. I use [1Password](http://agilebits.com), so filling out credit card and address forms is about a hundred times easier for me than for regular people who don't have 1Password (my heart goes out to them). But even with that, the PayPal checkout process is so much easier that I breathe an audible sigh of relief.

But PayPal has proven time and time again that they are a terrible, awful company without any thought to elegance or user experience. The founder [doesn't like people](http://www.telegraph.co.uk/news/worldnews/northamerica/usa/8721536/Paypal-founder-invests-in-floating-island-utopia.html), and he especially hates poor people, so I guess the total lack of respect for human beings makes sense. They just happen to be the only ubiquitous player on the web.

Implementing a PayPal payment system makes any self-respecting designer feel sick with shame, and we don't even have to talk about their Send and Receive money feature (supposedly their flagship service) where they put confusing holds on payments and take 3-5 business days to transfer to your bank account and make you feel all stabby and get the taste of blood in your mouth.

So before we can implement a fancy slick iframe interface for payments, we need to decide who will be the processor of those payments.

The keys will be:

1. It must allow _truly instant_ transfers of money with no limits, no holds, no bullshit.

2. It will probably need to have a huge, trusting, installed base.

The only people I can see with a chance to do this would be Amazon (who for some reason has not pushed their web payments service very hard), Apple (who makes enough money on their core business of selling deliciously wonderful hardware that they may not want to muddy the waters with a contentious service offering like web payments, where there is a major risk of bad PR and customer dissatisfaction if everything isn't perfect... people get sensitive about their money), or, and this is something like Baekdal is talking about, a consortium of major banks and credit card companies. A company with joint interests from the Bank of Americas and Wells Fargos and Visas and Mastercards of the world. They would be positioned to do something like this, and they could cut out the middle men and make us all happier.

But they won't. You know why? Because they are fucking worthless, pathetic dinosaurs. Try using Wells Fargo's new Send Money service _to another Wells Fargo customer_ and when it tells you it will take one business day or when it tells you that you have reached your arbitrary $2,000 limit of sending for the month, try to keep yourself from punching the wall, because that never solves anything.

via [@wes_garnett](http://twitter.com/wes_garnett)