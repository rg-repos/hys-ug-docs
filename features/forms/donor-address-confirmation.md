# Donor Address Confirmation

### Donor Address Confirmation

Sending the Donor's Address to Stripe or Authorize

When a Credit card transaction is run, it's up to you whether you want to send the address information along to the credit card processor (Stripe or Authorize.)

**Reasons to send the address**

1\. Banks and Credit Card companies will be more likely to approve donor transactions if the address is included.

2\. If you are running large dollar amount transactions, they are more likely to be scrutinized, so sending the address along is essential.

3\. If you send the Address, it will be stored in two places (HYS and the CC processor.) Redundancy is good.

**Reason not to send the address**

The only reason I can think of would be to offer greater simplicity in your donor signup form.&#x20;

How to send the address

After you have created your Donor form it will should look something like this.

There are 4 pieces of information that may be sent along to the Credit Card Processor

1\. Address

2\. City

3\. State

4\. Zip Code

To select the Address field you wish to send to the Credit Card processor, click on the pencil next to the address field.

Then change the field type to "Payment Gateway Address" and click Save.

Your Donor Form should now look like this:&#x20;

\


If the "Note: this field will post to Stripe/Authorize as the Address" message fails to appear, you most likely have not correctly setup your payment gateway, go set up [Stripe](broken-reference) or [Authorize](broken-reference), then come back here.

The most important fields for the Credit Card processor to verify the identity of your donors are the address field and the Zip Code field.

To set up the zip code, click on the pencil next to the "zip code" field and change the field type to "Payment Gateway Zip Code" like so:

\


Use the same procedure to setup the "Payment Gateway City" and "Payment Gateway State" and you will be good to go.

Once they are all configured properly, your Donor form should look like this:

Double check your setup!

Be sure to check that the fields have the correct corresponding field types. If you set the "City" field as the "Payment Gateway Address" field type, it will send the wrong information to the address field! Be careful!
