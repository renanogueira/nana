# Music Synchronizer

This is a Python project aimed at facilitating the synchronization of music libraries across different devices, maintaining a consistent folder hierarchy, and ensuring that only the server holds the true source of music.

## Key Features:

- **Change Detection:** The server monitors its music library for changes and notifies clients when new songs are added or modified.
  
- **User Authentication:** Users must authenticate to access the music library on the server, ensuring security and access control.
  
- **Automatic Download on Clients:** Clients automatically download added or modified songs from the server, keeping their libraries up to date.
  
- **Folder Hierarchy Maintenance:** The server and clients maintain the same folder structure, ensuring organization and consistency in the music library.

## Technologies Used:

- **Python:** Primary programming language for server and client development.
  
- **Flask:** Web framework used to create the server and its access routes.
  
- **watchdog:** Library used to detect changes in the server's file system.
  
- **Requests:** Library for making HTTP requests used for downloading music on clients.

## How to Contribute:

- Fork the repository.
  
- Clone the fork to your development environment.
  
- Implement enhancements or fixes and commit your changes.
  
- Push your changes to your fork.
  
- Send a pull request for review.

## License:

This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute it, provided you maintain the copyright notice and the original license.
