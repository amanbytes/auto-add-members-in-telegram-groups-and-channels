# A simple script to export members from Telegram Groups and Channels to a CSV file and to automatically add members to Telegram Groups.

> Exporting and adding members to channels requires the user from which the script is launched to be a Channel admin.

### Watch this YouTube Video To Know How To Use This Script:
[Auto Add Members In Telegram Group](https://youtu.be/WThZuzpswsw)

### Install dependencies

### **python3** and **pip3** must be installed and available in your PATH.

### install telethon module by executing command 
      pip3 install telethon

### Telegram Configuration

1. To run it you need to generate API credentials for your Telegram user, you can do it [here](https://core.telegram.org/api/obtaining_api_id), and access your already created ones [here](https://my.telegram.org/apps)
2. Replace your credentials in the python script

    ```
    api_id = 12345    # Your API ID

    api_hash = 'XXXXXXXXXXXXXXX'    # Your API Hash

    phone = '+11234567890'     # Your Phone Number With Country Code.
    ```

### Exporting users

Just follow the instructions in the script after running it from your shell.

### Adding users to groups

Users can be added using:

- **Username**: Gets temporarily banned with less requests.

- **User ID**: Gets temporarily banned with more requests.

> *Temporarily bans lasts for up to a day*

Adding users by Username expects a CSV file with one username per line.
Adding users by User ID expects a CSV file such as: `username,user_id,user_access_hash`
