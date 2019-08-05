# Networking-with-REST-API-calls-and-URLSession,Unit Tests and Data-Persistance-in-Core-Data
Project still in progress... Networking in Swift with REST API calls and URLSession, that puts the parsed JSON Data in a TableView and persists the data using Core Data with CRUD (create, read, update, and delete). I used also Unit Tests to test URLSession asynchronous network operations and make the project as robust as possible. When the JSON data is parsed into the TableView we can easily delete the cell with a swipe, the TableView will then reload itself and Core Data will update and save the changes in realtime. There is also an option to send HTTP GET requests to the JSONPlaceholder server.

This whole project is created completely programmatically without Storyboards and Interface Builder.
___
## Side Note
* Currently, I do not have an iPhone, so I'm unable to test the app on a physical device. I apologize in advance for maybe possible bugs.

   Kind regards,

   Ilija 🖖 😄
___

## Requirements
- Swift 4.2+
- Xcode 9.2+
- iOS 11.0+
___

## Getting the files

* Use GitHub to clone the repository locally, or download the .zip file of the repository and extract the files.
___

## License
```
MIT License

Copyright (c) 2019 Ilija Mihajlovic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
