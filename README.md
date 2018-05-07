# made

Mac Automated Development Environment

----

[macOS](https://en.wikipedia.org/wiki/MacOS)

* OS X 10.11 El Capitan was released on September 30, 2015. Similar to Mac OS X 10.6 Snow Leopard, Apple described this release as containing "refinements to the Mac experience" and "improvements to system performance" rather than new features. Refinements include public transport built into the Maps application, GUI improvements to the Notes application, adopting San Francisco as the system font for clearer legibility, and the introduction of System Integrity Protection. The Metal API, first introduced in iOS 8, was also included in this operating system for "all Macs since 2012".

* macOS 10.12 Sierra was released to the public on September 20, 2016. New features include the addition of Siri, Optimized Storage, and updates to Photos, Messages, and iTunes.

* The fall release of macOS 10.13 High Sierra was announced on June 5, 2017 at Apple's WWDC event. On September 12, 2017 at Apple's iPhone event, they announced its release to be September 25, 2017. Like OS X El Capitan and OS X Mountain Lion, High Sierra is a refinement-based update having very few new features. High Sierra uses the new Apple File System and includes enhancements to Safari, Photos, and Mail, among other changes.

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

----

1. Install latest OS X / macOS from USB thumb drive.

2. Install updates from App Store.

3. Setup System Preferences.
   1. Set ‘Use dark menu bar and Dock’ in General.
   2. Set Google Chrome as ‘Default web browser’ in General.
   3. Set ‘Screen Saver’ to Message in Desktop & Screen Saver.
   4. Set ‘Start after’ to 5 minutes in Desktop & Screen Saver.
   5. Set ‘Show with clock’ in Desktop & Screen Saver.
   6. Set lower right Hot Corner to ‘Start Screen Saver’ in Desktop & Screen Saver.
   7. Add more Spaces in Mission Control.
   8. Set ‘Computer Name’ to aslan in Sharing.
   9. Set ‘Use a 24 hour clock’ in Date & Time | Clock.
   10. Set ‘Display login window as: Name and Password’ in Users & Groups | Login Options.
   11. Set ‘Position on screen’ to Left, check ‘Automatically hide and show the Dock’, check ‘Magnification’ in Dock.
   12. Check '24-Hour Time' in Language & Region.
   13. Set 'Require password' to immediately in Security & Privacy.
   14. Check 'When the display is sleeping' Turn on Do Not Distrub in Notifications.
   15. Add local user to 'Allow access for only these users' in Sharing | Remote Login.
   16. Set preferences in iCloud.
   17. Lock screen with ‘control + shift + eject’ or ‘control + shift + power’. 'control + command + q' also works.
   18. Set Schedule to 'Sunset to Sunrise' under Display | Night Shift.

4. Install apps from App Store.
    1. Blackmagic Disk Speed Test
    2. Kindle
    3. Moom

5. Install Xcode Command Line Tools.
    ```bash
    xcode-select --install
    ```

6. Setup homebrew & ansible.
    ```bash
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    brew update -v && brew upgrade -v
    brew install python3
    pip3 install ansible
    ansible-playbook -c local -i hosts main.yml --check
    ansible-playbook -c local -i hosts main.yml
    ```

7. Change shell to /usr/local/bin/bash.

    [Upgrade to bash 4](http://clubmate.fi/upgrade-to-bash-4-in-mac-os-x/)

    [Change shell to bash 4](https://stackoverflow.com/questions/453236/how-to-set-my-default-shell-on-mac)

    [Changes in bash 4](http://tldp.org/LDP/abs/html/bashver4.html)

    [.bash_profile on macOS](https://scriptingosx.com/2017/04/about-bash_profile-and-bashrc-on-macos/)

    [bash environment variables](https://scriptingosx.com/2017/04/on-bash-environment-variables/)

    [bash aliases & functions](https://scriptingosx.com/2017/05/configuring-bash-with-aliases-and-functions/)

8. Install packages with pip3.

9. Install packages with gem.

10. Install packages with go get.

11. Install extra software.

----
