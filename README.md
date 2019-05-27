# Takeaway Challenge
==================
```
                            _________
              r==           |       |
           _  //            |  M.A. |   ))))
          |_)//(''''':      |       |
            //  \_____:_____.-------D     )))))
           //   | ===  |   /        \
       .:'//.   \ \=|   \ /  .:'':./    )))))
      :' // ':   \ \ ''..'--:'-.. ':
      '. '' .'    \:.....:--'.-'' .'
       ':..:'                ':..:'

 ```
The takeaway challenge is a 'Friday Challenge' set to try and test your knowledge of OOD, unit testing, feature testing, classes, methods, encapsulation, delegation and testing in isolation.

## Description
The program should allow a customer to see a list of dishes with prices, select some number of several available dishes, check that the total price displayed matches the sum of the dishes in the order and send an sms message (e.g. "Thank you! Your order was placed and will be delivered before 18:52") after the order is placed.

### NOTE:
"Place the order by giving the list of dishes, their quantities and a number that should be the exact total. If the sum is not correct the method should raise an error" - I have interpreted this as in passing in the money the customer wants to pay with. If they pass in more than the total, the extra will be seen as a tip, if less is passed in, then an error is raised.

## Installation
You will need to install bundle.
You will also need to set the following environment variables in a twilio.env file:
```
TWILIO_ACCOUNT_SID='<Please request the account SID or use your own from your own Twilio account>'
TWILIO_AUTH_TOKEN='<Please request the auth token or use your own from your own Twilio account>'
TWILIO_FROM_NUM='<Please request the Twilio number or use your own from your own Twilio account>'
TWILIO_TO_NUM='<Your mobile number>'
```
This file will be added to the .gitignore if named correctly. This is important if you are wanting to request to commit changes to this repository.

## Roadmap
A future release may include the functionality of being able to place an order via sms message.

## Authors and acknowledgment
Thanks to Makers Academy for setting this challenge.

## License
Please ask permission from the owner of this repo.

## Project status
This project is complete in terms of the required functionality. However, I have not been able to hit 100% test coverage due to including the environment variables. I am looking to continue researching this area and implementing what I find into this project in the near future.
