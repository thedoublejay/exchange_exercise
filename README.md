## La Coco Crypto Exchange
> This task should take about 2-6 hours of your time.

Mr. Ernesto Dela Cruz is planning to setup his own online cryptocurrency exchange. His exchange, La Coco Crypto Exchange will accept the supported cryptocurrencies and convert it to a different cryptocurrency.

### User Acceptance Criteria

Mr. Ernesto needs your help to create an app that will serve as his online exchange. The app can be on any platform (e.g, Mobile, Web or Desktop). The goal of this app is to be able to display the conversion amount for each token.

If User A wants to swap 1 BTC to ETH, it should display the corresponding ETH to be received. (e.g, 1 BTC = 16.47 ETH).

The app should do the following:

1. Display his store name and current date/time - **La Coco Crypto Exchange**
2. Should support these cryptocurrencies - **BTC, ETH, USDT, DFI, DOGE**
3. Should have two input fields
   1. Input #1 - Token to swap
   2. Input #2 - Token to receive
4. On change of input #1 or input #2, both fields should recalculate. Meaning, if I change input 1, input 2 will display the amount to receive. If I change input 2, input 1 will display the amount I need.
5. Both inputs should be able to switch to other currency
6. Should not be able to select on same currency on both fields

Bonus:
1. Prices should be displayed (e.g, 1 BTC = 16.47 ETH)
2. Should have a swap button. When clicked, it will reverse the currencies. (e.g, BTC => ETH, Press swap, ETH => BTC)

### Technical Requirements

1. For this app, you may create it on any platform (desktop, web or mobile app). You need to use the following tech stack below. Feel free to add any to the stack if you need, as long as these core frameworks are used. **You only need to select one platform.**

| App              | Tech Stack                     |
|------------------|--------------------------------|
| Mobile           | React Native, Expo, TypeScript |
| Desktop          | React, Electron, TypeScript    |
| Web              | React, Next.js, TypeScript     |

2. Use crypto prices from 
```http request
https://www.coingecko.com/en/api/documentation
```
3. Please provide a documentation on how to test and run your application.
4. Design of the app is up to you. Design should be responsive.

Bonus:
1. Unit or E2E tests

### Submission

1. Create your own private Git repo. Please invite [@thedoublejay](https://github.com/thedoublejay) to view your work once you are done.
2. **Manage your time well**, take note of the 2-6 hours specified. You are not expected to spend more than a day on this.
3. Email `jj@cakedefi.com` and cc `al@cakedefi.com` for submission.

1. Title: `${YOUR_NAME}: La Coco Crypto Exchange`
2. Body:
   1. GitHub Repo URL (with invitations)
   2. Short write-up of what you have done.
   3. Any suggestions for improving this task. (optional)
   4. Anything stands out to you. (optional)
   5. Comments (optional)