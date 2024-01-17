# RoyalPrince Donchian EA

This code is a sample Expert Advisor (EA) for the mql5 platform. The EA is developed by Forex Robot Easy Team and can be used to optimize forex trades with dynamic settings.

## Features

- Fixed Lots: The EA allows you to set a fixed lot size for your trades. The default value is 0.1.
- Hard Take Profit and Stop Loss: You can choose to use hard take profit (TP) and stop loss (SL) levels for your trades. The default values are 100 points for TP and 50 points for SL.
- Dynamic Donchian Channel Indicator: The EA utilizes the dynamic Donchian channel indicator to determine entry and exit points for trades.

## How it Works

1. The EA initializes by setting up the indicator and other necessary variables.
2. On each tick, the EA retrieves the current open tick price.
3. The trading logic is implemented in the 'Trading logic goes here' section, where you can define your own strategy.
4. If hard TP is enabled, the EA calculates the TP level based on the open tick price and the specified TP value. It then places a TP order.
5. If hard SL is enabled, the EA calculates the SL level based on the open tick price and the specified SL value. It then places a SL order.
6. The EA repeats this process on each tick.
7. When the EA is stopped or removed, the 'OnDeinit' function is called to perform any necessary cleanup and resource deallocation.

## User Guide

Please refer to the user guide or documentation provided by Forex Robot Easy Team for detailed instructions on how to use the RoyalPrince Donchian EA. The user guide covers topics such as setting fixed lots, hard TP and SL, and utilizing the dynamic Donchian channel indicator.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/royalprince-donchian-ea-review-optimize-forex-trades-with-dynamic-settings/). Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Test Plan and Test Cases

Please refer to the test plan and test cases provided by Forex Robot Easy Team for testing the functionality and reliability of the RoyalPrince Donchian EA. The test plan outlines the steps to be followed and the expected results for each test case.
