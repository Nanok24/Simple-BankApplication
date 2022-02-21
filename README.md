# Simple Banking Application

This is a demonstrative project where I learned how to work with arrays, numbers, dates, INTL (Localize data) and timers in JavaScript, using a real case scenario.

![Bankinst Presentation](/BankistPresentation.png)

### How to accces the application

The application has a fake login system (it doesn't use any OAuth tokens or store anything about the users) and has a few hard coded users with different balance values and transaction history (movements).

For the user input, type in the initials of the account name and for the pin field use the appropriate pin number associated to that account user.

This table of info should be of more help.

|       **Account**        | **User** | **Pin** |
| :----------------------: | :------: | :-----: |
|   _Jonas Schmedtmann_    |    js    |  1111   |
|     _Jessica Davis_      |    jd    |  2222   |
| _Steven Thomas Williams_ |   stw    |  3333   |
|      _Sarah Smith_       |    ss    |  4444   |

The first two accounts also have a different locale set to them as an attribute so you can see the diference in the currency and date formatting between them (Euros and dollars; european and american way to write the date)

### Functionalities

You can transfer money to anoter account, request a loan from the bank or even close the currently accessed account.

The application will update the transaction history accordingly and it also displays interesting statistics. For example you can see how much money you have collected, how much money you spent and how much money you are accumulating based on your interest rate.

I have also implemented a fake automatically log out system using a JS timer and you can also descendingly sort the transactions history.

### Credits

This is a project that was made during my learning process of JS, following Jonas Schmedtmann's (https://codingheroes.io/) course for javaScript. Credits to him for this idea and the provided structure
