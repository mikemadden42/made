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

* macOS Ventura (version 13) is the 19th major release of macOS, Apple's desktop operating system for Macintosh computers. It was announced at WWDC 2022 on June 6, 2022, and released on October 24, 2022. Key new features include Stage Manager, which helps users organize open apps and windows into groups, making multitasking easier. System Settings underwent a complete redesign, shifting towards an iOS-like interface. Updates were also made to Spotlight search, Mail, Safari (including Passkeys for password-less login), and gaming with Metal 3, enhancing graphics performance and gameplay.

* macOS Sonoma (version 14) is the 20th major release of macOS. Announced at WWDC 2023 on June 5, 2023, and released on September 26, 2023, macOS Sonoma introduced significant improvements in performance, productivity, and personalization. It includes interactive desktop widgets, bringing dynamic content directly to the desktop from various apps. A new Game Mode optimizes system resources for gaming, offering smoother gameplay and lower latency with accessories like wireless controllers and AirPods. macOS Sonoma also enhances video conferencing with advanced presenter overlays and reactions that respond to gestures. Safari was updated with profiles for better organization and advanced web apps.

----

1. Install latest OS X / macOS from USB thumb drive or the Recovery Partition.

1. Setup System Preferences.

For macOS 13 and newer, use these [settings](system-settings.md).

Otherwise, use these older settings.

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

1. Install apps from App Store.
    * Amazon Kindle
    * Keynote
    * Windows Apps - Microsoft Remote Desktop
    * Numbers
    * Okta Verify
    * Pages
    * Xcode

1. Install Xcode Command Line Tools.

    ```bash
    xcode-select --install
    ```

1. Setup homebrew & ansible.

    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    brew update -v && brew upgrade -v
    brew install ansible poetry python3
    git clone https://github.com/mikemadden42/mac-automation.git
    cd mac-automation
    ./setup-apple-apps.sh
    update-brew.sh
    ```

    Set the font size to `16` for iTerm.

    To enable key-repeating execute the following in your Terminal and restart VS Code:

    ```bash
    defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
    ```

1. Install packages with go get.

    ```bash
    update-go.zsh
    ```

1. Update rust.

    ```bash
    update-rust.sh
    ```

1. Build common C, C++, Swift projects.

1. Install Visual Studio Code extensions.

```bash

code --install-extension EXT_NAME

charliermarsh.ruff
DavidAnson.vscode-markdownlint
DimitarNonov.jellybeans-theme
frhtylcn.pythonsnippets
golang.go
idleberg.applescript
ms-azuretools.vscode-docker
ms-python.python
ms-vscode.powershell
ms-vscode.Theme-TomorrowKit
nimsaem.nimvscode
redhat.vscode-xml
redhat.vscode-yaml
rust-lang.rust-analyzer
ryanolsonx.zenburn
sswg.swift-lang
tamasfe.even-better-toml
vadimcn.vscode-lldb
vscodevim.vim
wholroyd.jinja

code --list-extensions
```

----
