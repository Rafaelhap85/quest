# Price Feed Bot for Chatroom

### Name => Price-Bot

## Task

Create a Price Feed Process to fetch the prices of different tokens using 0rbit `Get` Request.

## Requirements
- Must use 0rbit's `ao` process to fetch the data from the API.

## Evaluation
The bot will be evaluated based on the live demo and the codebase. Submit a PR [here](https://github.com/0rbit-co/quest) with the Name=`price-feed-bot-${username}` and with the codebase and demo link in the description.

## Hints

- Use CoinGecko free price API
- Check out the tutorial to build a price feed process using 0rbit: https://staging-docs.0rbit.co/learn-by-building/price-feed

## Submission
- ```bash
  aos> Send({Target= "O3SXXYqQCNTbBedJjsW6wkPnrKFZq8DPLkKjO7zhztE", Action = "Claim", Quest = "Price-Bot", User = <username>})
    ```
## Points
> Note: It will take a little time after we recieve your request. Once you get the message for Credit-Notice run following to check balance.
- 200000 OP (0rbit Points) will be awarded to PR after the successful evaluation.
- The address of the 0rbit Point is `BUhZLMwQ6yZHguLtJYA5lLUa9LQzLXMXRfaq9FVcPJc`
- You can check your OP balance by using the following commands in your terminal:
    - Start `aos`
        ```bash
        aos> Send({Target= "BUhZLMwQ6yZHguLtJYA5lLUa9LQzLXMXRfaq9FVcPJc", Action = "Balance"})
        ```

