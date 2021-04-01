# Thunder Client
Thunder Client is a GUI based Rest API Client Extension for Visual Studio Code, hand-crafted by [Ranga Vadhineni](https://twitter.com/ranga_vadhineni) with simple and clean design. The source code is not open source. You can report any Bugs Or Feature requests here.

* Website - [www.thunderclient.io](https://www.thunderclient.io)
* Follow on Twitter for updates - [twitter.com/thunder_client](https://twitter.com/thunder_client)

### Story behind Thunder Client
* Read Launch Blog Post on [Medium](https://rangav.medium.com/thunder-client-alternative-to-postman-68ee0c9486d6)

## Usage
* Install the Extension, Click Thunder Client icon on the Action Bar. [Intro Video on Youtube](https://www.youtube.com/watch?v=NKZ0ahNbmak)
* Open Command Palette (Cmd+Shift+P) type ``thunder`` and select ``Thunder Client: New Request``

![](images/thunder-client.gif)

## Tech
* Thunder Client is built with **Javascript, Flexbox, Typescript, Ace Editor, Got, Nedb**. No javascript or bootstrap frameworks used.

## Features
* Send http/https API request using any of the methods GET, POST, PUT, DELETE, PATCH, HEAD and OPTIONS.
* The Response data supports **syntax hightlighting using ACE Editor** which can handle large responses easily, you can also view response in **Full Screen**
* **History, Collections and Environment** Tabs in the Action Bar View for quick access.
* **Authentication:** Basic Auth, Bearer Token and OAuth 2.0 are supported.
* **Headers:** You can send http headers to test api, with **auto-complete** support.
* **Post Body:** Send post body as Text, Json, Xml, Form Data and Form-Url-Encoded.
* **Graphql:** Send Graphql Query & Variables has syntax highlighting support.
* **Environment Variables:** Syntax highlighting support for environment variables just use `{{variable}}` syntax in most fields
* **Scriptless Testing:** Test APIs with GUI based functionality, no scripting knowledge needed.
* **Themes:** The extension also supports VS Code themes.

## Privacy
* Basic anonymised telemetry data of extension usage is collected using [vscode-extension-telemetry](https://github.com/Microsoft/vscode-extension-telemetry), No Personal or request data is collected. You can opt out using VS Code Settings [details here](https://code.visualstudio.com/docs/getstarted/telemetry)
* There is no backend or cloud sync currently, all the data is stored locally on your computer.

## Import/Export
* You can import or export Thunder Client collections data, useful to share with team mates.
* Currently you can import collection or Environment file from **Postman** also. ( other file formats support soon.. ).

## Run Collection
* You can test multiple requests using Collection, select `Run All` option from the collection menu.
* The collection runner will execute all requests and test cases and display the result.

## Scriptless Testing
I noticed we need to write lot of boilerplate code in Postman and other clients to do basic testing using scripting like status code equal 200. So I implemented GUI based tests, where you select couple of dropdowns to do most standard tests very easily without any scripting knowledge.

![](https://github.com/rangav/thunder-client-support/blob/master/images/thunder-client-tests.png?raw=true)

