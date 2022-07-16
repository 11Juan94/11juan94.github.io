---
title: Secure passwords
date: 2022-07-16 12:48:00 -0600
categories: [Security, Passwords]
tags: [passwords]
render_with_liquid: false
image:
 path: /assets/img/posts/passwords.png
 width: 1280 # in pixels
 height: 905 # in pixels
 alt: passwords
---

Have you ever wonder how can I have dozen of passwords and always remember it without any effort?

Every day we hears news about persons who steal it's password and login into their accounts to use it's. A common practice is to use the  contacts to request money, send messages or try to collect another sites passwords with family members. Are you a type of person who use the same password for all websites?
That's a common practice but a bad indeed, because when a site gets compromised others people now know your password and can use it on every site on internet and if you ever have account in that site they can login.

> Using the same password for 2 or more websites it's not recommended.
{: .prompt-danger }

# How long its a secure password?

So as you probably have read it on internet, a secure password consists in "at least" 10 characters with the combination of numbers (0-9), lowercase ASCII characters (a-z), uppercase ASCII characters (A-Z) and special characters (,#$^&=+]'";.,!@/?). 

![min_password](/assets/img/posts/min_password.png)
_Minimum acceptable password_

But a small is not acceptable with the evolution of technology, in a pair of years these passwords can be bad idea. So I must recommend to use your passwords with a least 16 characters with  lowercase, uppercase, numbers, and symbols.

![sec_password](/assets/img/posts/sec_password.png)
_Secure acceptable password_

But that will be difficult to generate and remember each one of this passwords, so lets define a custom way of generate this type of passwords and you always remember it.

# Building unique password with you own technique

Les begin and say most of the people include a site, date, person, animal in your passwords, and that not bad at all. Most people have a memorable site, or person, or date which never will forget and we will focus on that. So the first thing to do is to encounter a list of this "tokens" with the info you never forgot, for example the next ones:

1. France (My first vacations!)
2. 1Mancha$ (The name of my first pet! (one for first, $ in a replace of "s"))
3. 87-11 (The year, and the month on the birth date of my son)
4. L4g00nN3wJ3rs3y (Lagoon New Jersey, but customized with numbers)
You get the idea of generate these memorable places, dates, words, etc. And with that now you generate a extra information for the site you are applying the password, for example Twitter, answer the next questions an with that you can generate the unique password:

5. What's the use of the platform for you? (Twitts)
6. What is the first and last letter? (TR) [always in UPPER in my example]
7. What color it's? (Blue)
8. On which year are you joining? (2022)

And with that for example I can generate the following password

FranceTwitts1Mancha$TR87-11BlueL4g00nN3wJ3rs3y2022

![custom_password_1](/assets/img/posts/custom_password_1.png)
_Custom secure acceptable password for twitter_

And for another site?, well answer the same questions al you get a new one secure, for example amazon.

5. What's the use of the platform for you? (Shopping)
6. What is the first and last letter? (AN) [always in UPPER in my example]
7. What color it's? (Yellow)
8. On which year are you joining? (2019)

FranceShopping1Mancha$AN87-11YellowL4g00nN3wJ3rs3y2019

![custom_password_2](/assets/img/posts/custom_password_2.png)
_Custom secure acceptable password for amazon_

And for another site?, well answer the same questions and you get a new one.

> Also remember to active your 2 factor authentication if its supported by the website.
{: .prompt-tip }

# Even with that technique I always forgot the passwords
If you always forgot your passwords, remember there already exists solutions like 
- BitWarden (<https://bitwarden.com/>) [Recommendation, free]
- Lastpass (<https://www.lastpass.com/>) [Free but only in PC o Mobile]
- 1Password (<https://1password.com/>) [Paid, 3USD/Month approx.]
- Keeper (<https://www.keepersecurity.com/>) [Paid, 3USD/Month approx.]

But I must recommend to use a second factor way using a hardware, for example security keys like Yubico. 
> Have extra key in a safe place case of missing the principal you got another one in a safe place.
{: .prompt-tip }