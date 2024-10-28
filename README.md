# Youtube-View-Bot
A YouTube view bot created by UnreliableCode

![image](https://github.com/user-attachments/assets/2eff4e24-4423-4bb8-b387-3b1a55cecc51)

## Description
This application automates the process of generating views for YouTube videos by utilizing multiple WebView2 instances. It allows users to input URLs of the videos they want to promote and set the number of threads and refresh intervals for the automation process. 

## Features
- Multiple WebView2 instances to simulate different users.
- Adjustable refresh intervals to control how often the views are counted.
- Support for multiple URLs to be processed simultaneously.
- User-friendly interface with error handling and input validation.

## Requirements
- .NET Framework 4.8 or higher
- Windows OS
- Microsoft Edge WebView2 runtime installed

## Getting Started

### Installation
1. Clone or download the repository.
2. Open the project in Visual Studio.
3. Ensure that the .NET Framework 4.8 is targeted.
4. Build the project to restore dependencies and compile the application.

### Usage
1. Launch the application.
2. Enter the URLs of the YouTube videos in the designated text box (one URL per line).
3. Specify the number of threads you want to use.
4. Set the refresh interval in seconds.
5. Click the start button to begin the process.
6. To stop the bot, click the exit button.

### Example
To use the application, you can enter multiple YouTube video URLs, specify how many threads you want to run concurrently, and set a refresh interval. For instance:
```
https://www.youtube.com/watch?v=dQw4w9WgXcQ
https://www.youtube.com/watch?v=9bZkp7q19f0
```

## Notes
- Use this tool responsibly and be aware of YouTube's policies regarding artificial view counts. Misuse of this tool may result in penalties on your YouTube account.
- The refresh interval should be set to a reasonable value to avoid overwhelming the servers.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Microsoft for providing WebView2, which allows seamless integration of web technologies in Windows Forms applications.
