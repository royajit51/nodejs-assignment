# Node.js Assignment
### Assignment: Backend

You are building the API for a **pizza-delivery company**.

1. **New users** can be created, their information can be edited, and they can be deleted. We should store their *name*, *email address*, and *street address*.
2. Users can **log in** and **log out** by creating or destroying a JWT token.
3. When a user is logged in, they should be able to **GET all the possible menu items** (these items should be come from the Mongo Database). 
4. A logged-in user should be able to **fill a shopping cart with menu items**
5. A logged-in user should be able to **create an order**. You should integrate with the Sandbox of [Stripe.com](https://stripe.com/) to accept their payment. _Note:_ Use the stripe sandbox for your testing. [Follow this link](https://stripe.com/docs/testing#cards) and click on the "tokens" tab to see the fake tokens you can use server-side to confirm the integration is working.
6. When an order is placed, you should **email the user a receipt**. You should integrate with the sandbox of [Mailgun.com](https://www.mailgun.com/) for this. _Note:_ Every Mailgun account comes with a sandbox email account domain (whatever@sandbox123.mailgun.org) that you can send from by default. So, there's no need to setup any DNS for your domain for this task. [Read more here](https://documentation.mailgun.com/en/latest/faqs.html#how-do-i-pick-a-domain-name-for-my-mailgun-account).
7. An API endpoint for the report of all orders.
8. Validation of all the request methods.
9. Image upload of every menu item.
10. API should handle approx 10,000 requests/second. (Autocannon will be used for benchmarking and Postman will be used for testing APIs).

