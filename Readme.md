

<img src="https://raw.githubusercontent.com/SAP-Custom-Widget/ChatGptWidget/main/icon.png" width="100">

## SAP Custom Widget: Chat Gpt Widget
ChatGPT Custom Widget for SAP Analytics Cloud

![preview](https://raw.githubusercontent.com/SAP-Custom-Widget/ChatGptWidget/main/screenshot.png)

## Installation
To use this widget in your SAP application, follow these steps:

<a target="_blank" href="https://sap-custom-widget.github.io/?dl=ChatGptWidget"><img width="150" src="https://raw.githubusercontent.com/SAP-Custom-Widget/sap-custom-widget.github.io/main/download.png"/></a>
- Download the `ChatGptWidget.json` file from the URLs specified in the webcomponents property of the JSON.
- Go to your SAC Portal, select Analytic Application from the left side bar, and then go to the Custom Widget tab.
- Click on the + icon on the right side and select the `ChatGptWidget.json` file that you downloaded.
- You're done! You can now use it in your app.

## How to get ChatGPT apiKey?

- Log into your OpenAI account on the [OpenAI website](https://beta.openai.com).
- Click on the “View API Keys” button in the top-right corner of the page, or [Click Here](https://platform.openai.com/account/api-keys)
- Click on the “Create an API Key” button to generate a new API key.
- Done, Now use it to Custom Widget

## Methods
The widget has the following methods:

### Set Methods

|  Method | Parameter Type  | Description  |
| ------------ | ------------ | ------------ |
| setApiKey(apiKey) | string |  Set Api Key of ChatGPT |
| setMax_tokens(max_tokens) | integer |  Set Result Max Length |

### get Methods

|  Method | Return Type | Description  |
| ------------ | ------------ | ------------ |
| getApiKey()  | string |  return Api Key of ChatGPT |
| getMax_tokens()  | integer |  return Result Max Length |

## About
This widget is developed by [Rohit Chouhan](http://linkedin.com/in/itsrohitchouhan "Rohit Chouhan")

