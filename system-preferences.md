# system preferences

These steps cover macOS **Big Sur (11)** and **Monterey (12)**, the last releases to use **System Preferences** before it was replaced by **System Settings** in macOS 13 Ventura (see [system-settings.md](system-settings.md)). Where a setting differs between the two releases, the version-specific path is noted. Many panes require clicking the **padlock** at the bottom left and authenticating before changes can be made.

---

1. **Select 'Dark' Appearance**:
   - Go to **System Preferences** > **General** > **Appearance** and select **Dark**.

2. **Select 'Blue' Accent color**:
   - Go to **System Preferences** > **General** > **Accent color** and select **Blue**.

3. **Set Google Chrome as 'Default web browser'**:
   - Go to **System Preferences** > **General** > **Default web browser** and select **Google Chrome**.

4. **Set 'Screen Saver' to Message**:
   - Go to **System Preferences** > **Desktop & Screen Saver** > **Screen Saver** tab > Select **Message**. Click **Screen Saver Options…** to set the message text.

5. **Set 'Start after' to 5 minutes**:
   - Go to **System Preferences** > **Desktop & Screen Saver** > **Screen Saver** tab > Set **Start after** to **5 Minutes**.

6. **Set 'Show with clock' in Screen Saver**:
   - In the same **Screen Saver** settings, check **Show with clock**.

7. **Set lower right Hot Corner to 'Start Screen Saver'**:
   - Go to **System Preferences** > **Desktop & Screen Saver** > **Screen Saver** tab > **Hot Corners...** button > Set **Lower Right** corner to **Start Screen Saver**.

8. **Add more Spaces in Mission Control**:
   - Invoke **Mission Control** (press **F3**, **Control + Up Arrow**, or swipe up with four fingers). Hover near the top of the screen and click the **+** that appears in the upper-right corner to add a Space.

9. **Set 'Computer Name'**:
   - Go to **System Preferences** > **Sharing** > **Computer Name** and set your custom name.

10. **Set 'Use a 24-hour clock'** (menu bar clock display):
    - Go to **System Preferences** > **Dock & Menu Bar** > **Clock** (under **Menu Bar Only**) and check **Use a 24-hour clock**. The **Clock** tab in **Date & Time** was removed in Big Sur.
    - If the checkbox has no effect, the system-wide **24-Hour Time** setting in step 13 takes precedence.

11. **Set 'Display login window as: List of users'**:
    - Go to **System Preferences** > **Users & Groups**, click the padlock to unlock, then select **Login Options** (bottom of the user list) and set **Display login window as** to **List of users**.

12. **Configure Dock settings**:
    - Go to **System Preferences** > **Dock & Menu Bar**:
      - Set **Position on screen** to **Left**.
      - Check **Automatically hide and show the Dock**.
      - Check **Magnification** and adjust the slider.

13. **Check '24-Hour Time' in Language & Region** (system-wide time format):
    - Go to **System Preferences** > **Language & Region** > **General** tab and check **Time format: 24-Hour Time**.

14. **Set 'Require password' to 'immediately'**:
    - Go to **System Preferences** > **Security & Privacy** > **General** tab, check **Require password**, and set it to **immediately** after sleep or screen saver begins.

15. **Enable FileVault**:
    - Go to **System Preferences** > **Security & Privacy** > **FileVault** tab > Enable **FileVault** and save the recovery key as prompted.

16. **Turn on Firewall**:
    - Go to **System Preferences** > **Security & Privacy** > **Firewall** tab > Turn on the **Firewall**.

17. **Enable Full Disk Access for Terminal & iTerm2**:
    - Go to **System Preferences** > **Security & Privacy** > **Privacy** tab > **Full Disk Access**, unlock the padlock, and check **Terminal** and **iTerm2** (use **+** to add an app that isn't listed).

18. **Configure 'Do Not Disturb'**:
    - On **Big Sur (11)**: Go to **System Preferences** > **Notifications**, select **Do Not Disturb** at the top of the list, and check **When the display is sleeping** (a **From/to** time schedule is also available).
    - On **Monterey (12)**: Focus replaced the old Do Not Disturb settings and the **When the display is sleeping** trigger was removed. Go to **System Preferences** > **Notifications & Focus** > **Focus** tab, select **Do Not Disturb**, click **+** under **Turn On Automatically**, and add a **Time** schedule (for example, overnight).

19. **Restrict Remote Login to specific users**:
    - Go to **System Preferences** > **Sharing** > **Remote Login**, set **Allow access for:** to **Only these users:**, and add the local user.

20. **Set iCloud preferences**:
    - Go to **System Preferences** > **Apple ID** > **iCloud** (in the Apple ID sidebar) and configure your iCloud preferences.

21. **Lock screen shortcuts**:
    - **Control + Command + Q** locks the screen immediately.
    - **Control + Shift + Power** (or **Media Eject**) puts the displays to sleep, which locks the screen when a password is required immediately (step 14).

22. **Set Night Shift Schedule**:
    - On **Big Sur (11)**: Go to **System Preferences** > **Displays** > **Night Shift** tab and set **Schedule** to **Sunset to Sunrise**.
    - On **Monterey (12)**: Go to **System Preferences** > **Displays** > **Night Shift…** button and set **Schedule** to **Sunset to Sunrise**.

23. **Set alert style to Banners for apps**:
    - Go to **System Preferences** > **Notifications** > Select an app and choose **Banners** as the alert style.

24. **Show Bluetooth in the menu bar**:
    - Go to **System Preferences** > **Dock & Menu Bar** > **Bluetooth** and check **Show in Menu Bar**.

25. **Enable Automatic Graphics Switching** (MacBook Pro with two graphics processors only):
    - Go to **System Preferences** > **Battery** > **Battery** tab and check **Automatic graphics switching**. Big Sur replaced **Energy Saver** with **Battery** on laptops. If the checkbox isn't shown, the Mac has only one graphics processor.

26. **Disable Siri**:
    - Go to **System Preferences** > **Siri** and uncheck **Enable Ask Siri**.

27. **Disable Screen Time**:
    - Go to **System Preferences** > **Screen Time** > **Options** (bottom left) and click **Turn Off…**.

28. **Enable Touch ID**:
    - Go to **System Preferences** > **Touch ID** and click **Add a fingerprint**.

29. **Add a printer**:
    - Go to **System Preferences** > **Printers & Scanners** and click **+** to add a printer.

30. **Configure Time Machine**:
    - Go to **System Preferences** > **Time Machine**. Uncheck **Back Up Automatically** to stop scheduled backups, or click **Options…** to exclude drives or folders from backup.

---

For macOS 13 Ventura and later, see [system-settings.md](system-settings.md).
