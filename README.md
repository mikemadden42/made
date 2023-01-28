# made

Mac Automated Development Environment

----

[macOS](https://en.wikipedia.org/wiki/MacOS)

* OS X 10.11 El Capitan was released on September 30, 2015. Similar to Mac OS X 10.6 Snow Leopard, Apple described this release as containing "refinements to the Mac experience" and "improvements to system performance" rather than new features. Refinements include public transport built into the Maps application, GUI improvements to the Notes application, adopting San Francisco as the system font for clearer legibility, and the introduction of System Integrity Protection. The Metal API, first introduced in iOS 8, was also included in this operating system for "all Macs since 2012".

* macOS 10.12 Sierra was released to the public on September 20, 2016. New features include the addition of Siri, Optimized Storage, and updates to Photos, Messages, and iTunes.

* The fall release of macOS 10.13 High Sierra was announced on June 5, 2017 at Apple's WWDC event. On September 12, 2017 at Apple's iPhone event, they announced its release to be September 25, 2017. Like OS X El Capitan and OS X Mountain Lion, High Sierra is a refinement-based update having very few new features. High Sierra uses the new Apple File System and includes enhancements to Safari, Photos, and Mail, among other changes.

* The successor to macOS High Sierra, macOS Mojave was announced at the WWDC 2018, on June 4, 2018, and was released to the public on September 24, 2018. It brings several iOS apps to the desktop, including Apple News, Voice Memos, and Home; includes a much more comprehensive "Dark Mode", and is the final version of macOS to support 32-bit apps.

* macOS Catalina is the successor to macOS Mojave. It was announced at WWDC 2019 on June 3, 2019, and was released to the public on October 7, 2019. Catalina is the first version of macOS to support only 64-bit applications and the first to include Activation Lock. iTunes is replaced by separate Books, Music, Podcasts, and TV apps, in line with iOS. Zsh is the default login shell and interactive shell in macOS Catalina, replacing Bash, the default shell since Mac OS X Panther in 2003. Catalyst is a new software-development tool that allows developers to write apps that can run on both macOS and iPadOS.

* macOS Big Sur (version 11) is the seventeenth major release of macOS, Apple Inc.'s operating system for Macintosh computers. It was announced at Apple's Worldwide Developers Conference (WWDC) on June 22, 2020, and was released to the public on November 12, 2020. Most notably, macOS Big Sur features a user interface redesign that features new blurs to establish a visual hierarchy and also includes a revamp of the Time Machine backup mechanism, among other changes. It is also the first macOS version to support Macs with ARM-based processors. To mark the transition, the operating system's major version number was incremented, for the first time since 2000, from 10 to 11.

* macOS Monterey (version 12) is the 18th and current major release of macOS, Apple's desktop operating system for Macintosh computers. The successor to macOS Big Sur, it was announced at WWDC 2021 on June 7, 2021, and released on October 25, 2021. macOS Monterey includes Universal Control (which allows input devices to be used with multiple devices simultaneously), Focus (which allows selectively limiting notifications and alerts depending on user-defined user/work modes), Shortcuts (a task automation framework previously only available on iOS and iPadOS expected to replace Automator), a redesigned Safari Web browser, and updates and improvements to FaceTime.

----

With El Capitan, Apple brings never-before-seen features to OS X—like a split-screen
desktop, improved window controls, and amazing graphics.  The new edition of David
Pogue's #1 bestselling Mac book shows you how to use key new features such as swiping
gestures, Notes, a new Spotlight search system, the Safari pinning feature, and Split View.

With Sierra, Apple brings never-before-seen features to macOS—like Siri voice control,
file sharing across all your iOS devices, picture-in-picture mode for iTunes and Safari,
and AI photo search. Once again, David Pogue brings his humor and expertise to the #1
bestselling Mac book.

With High Sierra, Apple has taken its macOS operating system to new heights. From
Apple’s efficient new file system to improved video streaming and support for virtual
reality, this latest macOS version provides features improve your experience. And once
again, David Pogue brings his humor and expertise to the #1 bestselling Mac book.

With Mojave, Apple gives macOS new features and improvements both right on your desktop and under the hood. You'll see convenient new Finder features like Quick Actions and Desktop Stacks and benefit from improved online security. The new edition of David Pogue's #1 bestselling Mac book shows you how to use the revamped App Store, all-new apps like News and Stocks, FaceTime's new Group Chat, and Dynamic Desktop.

Apple gives macOS new features and improvements right on your desktop and under the hood with Catalina—aka OS X 10.15. With Catalina, you’ll learn how to use your iPad as a second screen, work with iPad apps on your Mac, and use Screen Time on your Mac. This new edition also includes revamped apps for Music, Podcasts, and TV.

----

1. Install latest OS X / macOS from USB thumb drive or the Recovery Partition.

2. Install updates from App Store.

3. Setup System Preferences.
   * Select ‘Dark’ Appearance in General.
   * Select 'Blue' Accent color in General.
   * Set Google Chrome as ‘Default web browser’ in General.
   * Set ‘Screen Saver’ to Message in Desktop & Screen Saver.
   * Set ‘Start after’ to 5 minutes in Desktop & Screen Saver.
   * Set ‘Show with clock’ in Desktop & Screen Saver.
   * Set lower right Hot Corner to ‘Start Screen Saver’ in Desktop & Screen Saver.
   * Add more Spaces in Mission Control.
   * Set ‘Computer Name’ to custom name in Sharing.
   * Set ‘Use a 24 hour clock’ in Date & Time | Clock.
   * Set ‘Display login window as: List of users’ in Users & Groups | Login Options.
   * Set ‘Position on screen’ to Left, check ‘Automatically hide and show the Dock’, check ‘Magnification’ in Dock.
   * Check '24-Hour Time' in Language & Region.
   * Set 'Require password' to immediately in Security & Privacy.
   * Enable filevault & save recovery key.
   * Turn on firewall in Security & Privacy | Firewall.
   * Enable Full Disk Access for Terminal & iTerm in Security & Privacy | Privacy.
   * Check 'When the display is sleeping' Turn on Do Not Distrub in Notifications.
   * Add local user to 'Allow access for only these users' in Sharing | Remote Login.
   * Set preferences in iCloud.
   * Lock screen with ‘control + shift + eject’ or ‘control + shift + power’. 'control + command + q' also works.
   * Set Schedule to 'Sunset to Sunrise' under Display | Night Shift.
   * Set alert style to Banners for apps in Notifications.
   * Check Show Bluetooth in menu bar in Bluetooth.
   * Enable Automatic graphics switching in Energy Saver.
   * Disable Siri.
   * Disable Screen Time.
   * Enable Touch ID.
   * Add a printer.
   * Disable Time Machine.

4. Install apps from App Store.
    * Blackmagic Disk Speed Test
    * Keynote
    * Kindle
    * Microsoft Remote Desktop 10
    * Moom
    * Novabench
    * Numbers
    * Pages
    * Slack

5. Install Xcode Command Line Tools.

    ```bash
    xcode-select --install
    ```

6. Setup homebrew & ansible.

    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    brew update -v && brew upgrade -v
    brew install python3
    pip3 install ansible
    # May only be needed on macOS 10.15
    export DYLD_LIBRARY_PATH=/usr/local/opt/openssl/lib:$DYLD_LIBRARY_PATH
    ansible-playbook -c local -i hosts dev.yml --check
    ansible-playbook -c local -i hosts dev.yml
    ansible-playbook -c local -i hosts rust.yml --check
    ansible-playbook -c local -i hosts rust.yml
    update-brew.sh
    ```

    Set the font size to `16` for iTerm.

    To enable key-repeating execute the following in your Terminal and restart VS Code:

    ```bash
    defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
    ```

    Consider adding `/usr/local/sbin` to the `PATH` for apps like mtr.

7. Change shell to /usr/local/bin/zsh.

    [My favourite Zsh features](https://code.joejag.com/2014/why-zsh.html)

    [Why zsh is Cooler than Your Shell](https://www.slideshare.net/brendon_jag/why-zsh-is-cooler-than-your-shell?next_slideshow=1)

    [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/)

8. Change shell to /usr/local/bin/bash.

    [Upgrade to bash 4](http://clubmate.fi/upgrade-to-bash-4-in-mac-os-x/)

    [Change shell to bash 4](https://stackoverflow.com/questions/453236/how-to-set-my-default-shell-on-mac)

    [Changes in bash 4](http://tldp.org/LDP/abs/html/bashver4.html)

    [.bash_profile on macOS](https://scriptingosx.com/2017/04/about-bash_profile-and-bashrc-on-macos/)

    [bash environment variables](https://scriptingosx.com/2017/04/on-bash-environment-variables/)

    [bash aliases & functions](https://scriptingosx.com/2017/05/configuring-bash-with-aliases-and-functions/)

9. Install packages with pip3.

    ```bash
    sudo mkdir /usr/local/man
    sudo chown $USER /usr/local/man
    update-pip3.sh
    ```

10. Install packages with go get.

    ```bash
    update-go.sh
    ```

11. Update docker.

    ```bash
    update-docker.sh
    ```

12. Update rust.

    ```bash
    update-rust.sh
    ```

13. Update iTerm2 fonts.

<https://github.com/Peltoche/lsd/issues/199#issuecomment-494218334>

14. Install poetry.

<https://python-poetry.org/docs/master/>

15. Build common projects.

* C
* C++
* Swift

16. Setup sudo & Touch ID.

<https://davidwalsh.name/touch-sudo>

```bash
# Open the sudo PAM config file.
sudo vim /etc/pam.d/sudo

# Add the following as the first line after initial comments.
auth sufficient pam_tid.so

# Save the confile file.
:wq!
```

17. Install Visual Studio Code extensions.

```bash

code --install-extension EXT_NAME

bungcip.better-toml
DavidAnson.vscode-markdownlint
DimitarNonov.jellybeans-theme
frhtylcn.pythonsnippets
golang.go
idleberg.applescript
matklad.rust-analyzer
ms-azuretools.vscode-docker
ms-python.python
redhat.vscode-commons
redhat.vscode-yaml
vscodevim.vim
wholroyd.jinja

code --list-extensions
```

18. Install pyenv.

<https://github.com/pyenv/pyenv-installer>

----
