# SignalR: Chat (Advanced)

Client-Server Communication System

Basic Idea behind the Project: For the successful completion of a project on time in the software industry, it is very important for the administration, project leaders, and the team members, i.e. the programmers should have smooth and regular communication among themselves. So, it becomes really important to have a platform to do so. Hence we have our Client-Server Communication System.

# Project Description:
A web-based project developed in ASP.NET, allows the administrator to communicate between the project leaders and programmers and allows them to maintain the login and logout time. The project also maintains offline messages, i.e. the messages that were sent online, can be viewed even when you are offline, but obviously, you cannot send any message when you are offline. The main features of the Client-Server Communication system are

Sending Messages: The project leader can interact with each and every programmer using this software.
Chatting: Communication with a colleague will be made easy using the chat option.
Login and Logout Time: When a programmer logs in, the login time is recorded and also the logout time is recorded. This report will be sent to the project leader so that they can ensure that everybody is working fine. Also, the login and logout times of the project leaders will be visible to the admins. 
Hence, admin is the highest in the hierarchy, and then come the project leaders, and the lowest level in the hierarchy is that of the programmers.
The Link to a sample Chat-Application (example for Client Server Communication) along with its source code is given below. You can refer to it and make your own version of it.

[![Deploy App](https://github.com/IEvangelist/signalr-chat/actions/workflows/blazing-chat.yml/badge.svg)](https://github.com/IEvangelist/signalr-chat/actions/workflows/blazing-chat.yml)

## Run locally

To run locally, you'll need to have several environment variables created. The `configuration` object is expecting a value that doesn't exist. For the translator specifically, you'll need to create an Azure account, and corresponding Azure resource for the translator. There is a free tier, you can sign up here:

[Azure Translator Docs: Create a Translator resource](https://docs.microsoft.com/azure/cognitive-services/translator/translator-how-to-signup?wt.mc_id=dapine)

#### Environment Variables

| Name | Value |
|------|-------|
| `TranslateTextOptions__ApiKey` | <Your Translator Resource's API key> |
| `TranslateTextOptions__Endpoint` | `https://api.cognitive.microsofttranslator.com/` |
| `TranslateTextOptions__Region` | <Your Translator Resource's Region> |

> After you've created the resource, and added the environment variables, close and reopen your IDE. It should then work.
