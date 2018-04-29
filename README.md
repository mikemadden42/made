# made

Mac Automated Development Environment

----

https://en.wikipedia.org/wiki/MacOS

- OS X 10.11 El Capitan was released on September 30, 2015. Similar to Mac OS X 10.6
Snow Leopard, Apple described this release as containing "refinements to the Mac
experience" and "improvements to system performance" rather than new features.
Refinements include public transport built into the Maps application, GUI improvements
to the Notes application, adopting San Francisco as the system font for clearer
legibility, and the introduction of System Integrity Protection. The Metal API, first
introduced in iOS 8, was also included in this operating system for "all Macs since 2012".

- macOS 10.12 Sierra was released to the public on September 20, 2016. New features
include the addition of Siri, Optimized Storage, and updates to Photos, Messages, and
iTunes.

- The fall release of macOS 10.13 High Sierra was announced on June 5, 2017 at Apple's
WWDC event. On September 12, 2017 at Apple's iPhone event, they announced its release
to be September 25, 2017. Like OS X El Capitan and OS X Mountain Lion, High Sierra is a
refinement-based update having very few new features. High Sierra uses the new Apple File
System and includes enhancements to Safari, Photos, and Mail, among other changes.

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

- Set ‘Use dark menu bar and Dock’ in General.
- Set Google Chrome as ‘Default web browser’ in General.
- Set ‘Screen Saver’ to Message in Desktop & Screen Saver.
- Set ‘Start after’ to 5 minutes in Desktop & Screen Saver.
- Set ‘Show with clock’ in Desktop & Screen Saver.
- Set lower right Hot Corner to ‘Start Screen Saver’ in Desktop & Screen Saver.
- Add more Spaces in Mission Control.
- Set ‘Computer Name’ to aslan in Sharing.
- Set ‘Use a 24 hour clock’ in Date & Time | Clock.
- Set ‘Display login window as: Name and Password’ in Users & Groups | Login Options.
- Set ‘Position on screen’ to Left, check ‘Automatically hide and show the Dock’, check
  ‘Magnification’ in Dock.
- Check '24-Hour Time' in Language & Region.
- Set 'Require password' to immediately in Security & Privacy.
- Check 'When the display is sleeping' Turn on Do Not Distrub in Notifications.
- Add local user to 'Allow access for only these users' in Sharing | Remote Login.
- Set preferences in iCloud.

- Lock screen with ‘control + shift + eject’ or ‘control + shift + power’.

4. Install apps from App Store.

Blackmagic Disk Speed Test
Kindle
Moom

5. Install Xcode Command Line Tools.

xcode-select --install

6. Setup homebrew & ansible.

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update -v && brew upgrade -v
brew install python3
pip3 install ansible
ansible-playbook -c local -i hosts main.yml --check
ansible-playbook -c local -i hosts main.yml

7. Change shell to /usr/local/bin/bash.

http://clubmate.fi/upgrade-to-bash-4-in-mac-os-x/
https://stackoverflow.com/questions/453236/how-to-set-my-default-shell-on-mac

http://tldp.org/LDP/abs/html/bashver4.html
https://scriptingosx.com/2017/04/about-bash_profile-and-bashrc-on-macos/
https://scriptingosx.com/2017/04/on-bash-environment-variables/
https://scriptingosx.com/2017/05/configuring-bash-with-aliases-and-functions/

8. Install packages with pip3.

9. Install packages with gem.

10. Install packages with go get.

11. Install extra software.

----
