# Vanadium Nuker v2.0.33

**A Discord server nuking tool that relies entirely on HTTP requests (no discord.py library).**  
Developed by **RussianHarvey & Tobakk**, modified for maximum speed via direct HTTP calls.

---

## 📥 Download & Run
- Download the executable file `Vanadium.exe` (no additional installation required).
- Run the file and the tool interface will appear.

---

## 🔧 Prerequisites
1. **Discord Bot Token** (the bot must be present in the target server).
2. **Server ID** (Guild ID) of the server you want to target.
3. **Bot Permissions**: Ensure the bot has the following permissions based on the operation:
   - Ban members: `BAN_MEMBERS`
   - Create/Delete channels: `MANAGE_CHANNELS`
   - Create/Delete roles: `MANAGE_ROLES`
   - Send messages: `SEND_MESSAGES` (for regular spam)
---

## 🚀 How to Use
1. Run `Vanadium.exe`.
2. Enter the **Bot Token**, then the **Server ID**.
3. The main menu will appear (see below).
4. Choose the operation number you want to execute.
---

## 📋 Options Overview

| Number | Operation         | Description                                                                 |
|--------|-------------------|-----------------------------------------------------------------------------|
| 1      | Ban Members       | Ban all members (you can fetch them first or use a previously saved file). |
| 2      | Create Channels   | Create a specified number of channels (text or voice).                      |
| 3      | Delete Channels   | Delete all existing channels in the server.                                 |
| 4      | Create Roles      | Create a specified number of roles (with random colors).                    |
| 5      | Delete Roles      | Delete all roles (except @everyone).                                        |
| 6      | Spam Channels     | Send a specified number of messages to existing text channels (round-robin).|

---

## ⚡ Speed Notes
- The tool uses **45 concurrent threads** (you can modify this number in the source code if needed).
- If you hit a **Rate Limit** (HTTP 429), the tool will automatically wait the required time and then continue.
- To increase speed, adjust the `__threads__` variable (for developers only).

---

## ⚠️ Important Warnings
- Using this tool against servers you do not own is **illegal** and violates Discord's Terms of Service.
- Excessive use may lead to **your bot or account being banned**.
- We are not responsible for any misuse of this tool.

---

## 📞 Support
- for help Contact me via Discord Discord Username : russianharve

---

## Developer 
- RussianHarvey
- Sulaiman(tobak)

**Happy nuking!** 😈
<img width="1463" height="701" alt="Screenshot 2026-03-02 171129" src="https://github.com/user-attachments/assets/7dc916ca-f14c-4831-a662-88e4d150966b" />

