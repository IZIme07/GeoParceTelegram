
### Introduction

Welcome to the user guide for **geoparse.exe**, version v1.0.0. This program is designed to search for Telegram users by geolocation. To operate the program, you need an **API ID** and **API Hash**, which can be obtained from [my.telegram.org](https://my.telegram.org/).

### Steps to Obtain API ID and API Hash

1. **Register on Telegram's Website:**

   - Visit the site [my.telegram.org](https://my.telegram.org/).
   - Log in using your phone number registered with Telegram.
   - You will receive a confirmation code in your Telegram app, which you should enter on the website.

2. **Getting the API ID and API Hash:**

   - After successful login, select the "Create New Application" option.
   - Fill in the required fields, such as the application name and a brief description.
   - Once the application is created, you will see your **API ID** and **API Hash**. Make sure to save them securely as you will need them for the program.

### Installation and Initial Run

1. **Running the Program:**

   - Run the program :
     ```
     geoparse.exe
     ```

2. **Initial Setup:**

   During the first run, you will be prompted to enter your **API ID** and **API Hash**. After entering them, these settings will be saved, and you won't need to re-enter them in future sessions.

### Authorization

1. **Authorization Process:**

   - After entering your **API ID** and **API Hash**, the program will connect to Telegram and request a confirmation code, which will be sent to your Telegram account.
   - Enter the received code in the terminal.

2. **Session Saving:**

   - Once authorized, the program will create a session file, which will save you from repeating the authorization process in subsequent runs.

### Using the Program

1. **Input Search Data:**

   When you run the program, enter the required data:

   - **Country code** in ISO format (e.g., GB for Great Britain).
   - **City name** in Latin letters (e.g., London). Leave empty if you wish to search the entire country.
   - **Tag key and value** (optional). This helps to narrow the search to specific places (e.g., `amenity=casino`).

   You can find the full list of keys and tags on the [OpenStreetMap Wiki](https://wiki.openstreetmap.org/wiki/Map_Features).

2. **Searching for Users:**

   - The program will start searching for users in the specified location and save the data to the `users_data.csv` file.
   - The data includes the user ID, name, username, distance, and status.

3. **Filtering Users:**

   - After the search is complete, the program will automatically filter users in the `users_data.csv` file.

### Updating the Program

- The program automatically checks for updates on GitHub.
- If a new version is available, the update process will be initiated using `updater.exe`.

### Logging

- All actions of the program, including errors, are recorded in the `app.log` file.

### Conclusion

You are now ready to use **geoparse.exe** to search for Telegram users by geolocation. If you have any questions or issues, please refer to the documentation or the repository on [GitHub](https://github.com/IZIme07/GeoParceTelegram).

---

Feel free to reach out if you need any further assistance. Good luck using the program!

if you want a contact with me, please use the Telegram @testxuser
