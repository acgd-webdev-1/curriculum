---
layout: lesson
title: "Install all the things!"
desc: "Set up your computer, install all the different web browsers, install a code editor, and set up GitHub Desktop."

hide_markbot: true
video: "-wwzFCj_keE"

important:
  title: "MacOS-specific tutorial"
  text: |
    If you have a Windows-based computer jump to the correct lesson.

    [**☛ Go to the Windows installation tutorial.**](/courses/web-dev-1/install-all-the-things-windows/)

steps:
  - title: "Configure Finder"
    before: |
      Let’s change a few settings on your computer to make development life easier.

      ![](finder.jpg)

      1. Go to `Finder > Preferences`.
      2. Go to “Advanced”.
      3. Make sure “Show all filename extensions” is checked.

  - title: "Configure keyboard preferences"
    before: |
      By default some of the keyboard features are turned off on MacOS—let’s fix that.

      ![](keyboard.jpg)

      1. Go to ` > System Preferences…`.
      2. Go to “Keyboard”.
      3. Go to the “Shortcuts” tab.
      3. Enabled full keyboard access to “All controls”.

  - title: "Install The Unarchiver"
    before: |
      This is a simple zip utility that’s much better than the one built into Mac OS X. *It’s one of those apps I install on every Mac I touch.*

      **If you have an Apple App Store account, search and install it from there.**

      ![](unarchiver.jpg)

      *If you don’t have an Apple App Store account (or forget your password):*

      1. [Download The Unarchiver](http://unarchiver.c3.cx/unarchiver) from the website.
      2. Unzip the downloaded file
      3. Drag the application to your “Applications” folder.

  - title: "Install Firefox"
    before: |
      ![](firefox.jpg)

      We need to install a bunch of browsers because, as web designers, we don’t know what browser someone will be using—so we need to test our websites in all of them.

      1. Go to Mozilla’s website and [download Firefox](http://getfirefox.com/).
      2. Mount the disk image by double clicking.
      3. Drag the application to your “Applications” folder.
      4. Eject the mounted disk from your computer.
      5. Delete the downloaded file.
    notes:
      - label: "Warning"
        text: "Make sure to only download Firefox directly from Mozilla—other websites may inject malware."

  - title: "Install Chrome"
    before: |
      ![](chrome.jpg)

      Go to Google’s website and [download Chrome](https://www.google.com/chrome/).
      *(Ditto steps above.)*

    notes:
      - label: "Warning"
        text: "Make sure to only download Chrome directly from Google—other websites may inject malware."

  - title: "Install Opera"
    before: |
      ![](opera.jpg)

      1. Go to Opera’s website and [download Opera](http://www.opera.com/).
      2. Unzip the download
      3. Double click the installer and let it do its thing.
      5. Delete the downloaded installer file.

    notes:
      - label: "Warning"
        text: "Make sure to only download Opera directly from Opera—other websites may inject malware."

  - title: "Configure Safari"
    before: |
      Safari’s web developer tools are turned off by default—so let’s turn them on.

      ![](safari.jpg)

      1. Go to `Safari > Preferences`
      2. Go to the “Advanced” tab.
      3. Make sure “Show Develop menu in menu bar” is enabled.

  # - title: "Create a BrowserStack account"
  #   before: |
  #     We want to be able to test Microsoft Edge, but because we’re using MacOS, that becomes a little more difficult.

  #     ![](browserstack.jpg)

  #     A simple way to test is using an online emulation service. *BrowserStack, sponsored by Microsoft, provides free Microsoft Edge testing.* So, we’re going to use that service.

  #     1. Go to [BrowserStack’s website](https://www.browserstack.com/test-on-microsoft-edge-browser#live-cloud) and create an account (press “Get Started”).
  #     2. You may be prompted to install something else for testing on `localhost`: Press “Yes” you want to do that, and install the extension.

  # - title: "Install VirtualBox"
  #   before: |
  #     We want to install Internet Explorer and Microsoft Edge on our computers but they browsers only run on Windows.

  #     To start, we have to install an emulator system that will allow us to run Windows alongside Mac OS X.

  #     ![](virtual-box.jpg)

  #     1. Go to the VirtualBox website and [download VirtualBox](https://www.virtualbox.org/wiki/Downloads).
  #       *Be sure to get the VirtualBox binary for **“OS X Hosts amd64”**.*
  #     2. Mount the disk image by double clicking.
  #     3. Double-click the “VirtualBox.pkg” installer file.
  #     4. Step through all the instructions—the defaults are good.
  #     5. Eject the mounted disk from your computer.
  #     6. Delete the downloaded file.

  # - title: "Install Internet Explorer 11 & Edge"
  #   before: |
  #     Normally you’d have to download IE/11 from [Microsoft directly](http://modern.ie)—but I’ve gone ahead and done that because it’s faster over the school network.

  #     1. Go to the Graphic Design Dropbox: `smb://dropbox.ottawa.ad.algonquincollege.com`
  #       <br>*To connect: in Finder, go to `Go > Connect to Server…`*
  #       <br>*The username and password is your Algonquin Wi-Fi password.*
  #     2. Go to my folder
  #       <br>`Faculty Folders > Thomas Bradley > Public`
  #     3. Look for a folder called “MS Browsers”.
  #     4. Drag the two files to your computer—**do not double click**.
  #     5. Unzip them both.
  #       *(If you get a `cpgz` file, try right clicking on the original `zip` and pressing `Open With > The Unarchiver`.)*
  #     6. You’ll be presented with an orange “ova” box icon—double click it.
  #     7. VirtualBox will request that you import—press “Import”.
  #     8. Wait…
  #     9. Delete the orange “ova” file and the zip afterwards.
  #   notes:
  #     - label: "Warning"
  #       text: "Do not double click the browser installers from within the dropbox!"
  #     - label: "Big files"
  #       text: "The installers for IE/11 and Edge are **huge** because we’re actually installing two complete copies of Windows on our computer."

  - title: "Get HTML files to open properly"
    before: |
      This will make it so double clicking HTML files opens your browser instead of a code editor.

      ![](get-info.jpg)

      1. <a href="fixer.html" download="fixer.html">Download this HTML file.</a>
        *(If clicking this link doesn’t download the file, `Right Click > Download Linked File`.)*
      2. In Finder, go to where it was downloaded (likely your “Downloads” folder) and right click—press “Get Info”.
      3. Under the “Open with” section, set it to “Firefox” or “Chrome”.
      4. Press “Change All…”.
      5. Close the info window and trash the HTML file.

  - title: "Install GitHub Desktop"
    before: |
      We need to install the GitHub Desktop application so that we can manage and upload our code to GitHub.

      1. Download the app from the [GitHub Desktop](https://desktop.github.com/) website.
      2. Unzip the downloaded file
      3. Drag the GitHub Desktop application icon to your “Applications” folder.

      ![](github-desktop.jpg)
      ![](github-desktop-user.jpg)

      **Make sure to sign in with your GitHub username, email address, and password.**

  - title: "Install the Command Line Tools"
    before: |
      We need to install some extra development tools on our computer so Markbot can work well.

      Open the application on your computer called “Terminal”, it can be found in `Applications > Utilities`

      Type exactly this:

      ```
      xcode-select --install
      ```

      Hit `Return`

      It will guide you through the download and installation process.

      ![](xcode-select-install.jpg)

  - title: "Install the Java Developer Kit"
    before: |
      We need to install the OpenJDK because the automated marking program, Markbot, needs access to Java for performing some of it’s tasks.

      Go to the OpenJDK download page on [Adopt OpenJDK](https://adoptopenjdk.net/) website.

      ![](jdk.jpg)

      **Choose the “Open JDK 11 (LTS)” version of OpenJDK at the bottom of the list.**

      1. Download the JDK for your computer.
      3. Double click the installer and let it do its thing.
      5. Delete the downloaded file.

  - title: "Install Markbot"
    before: |
      All of the coding exercises we do in this class will be using Markbot to automatically grade your work. So, we need to set that up.

      1. Download [Markbot](https://assets.learn-the-web.algonquindesign.ca/markbot/Install%20Markbot.dmg). (*or [Markbot for Windows](https://assets.learn-the-web.algonquindesign.ca/markbot/Markbot%20Setup.exe)*)
      2. Mount the disk image by double clicking.
      3. Drag the application to your “Applications” folder.
      4. Eject the mounted disk from your computer.
      5. Delete the downloaded file.

      **Open up Markbot and sign in with your GitHub username.**

      ![](markbot.jpg)

      ### Add your Progressinator API key

      Go back to your browser tab with your Progressinator profile & copy & paste the API key into Markbot:

      ![](markbot-api-key.jpg)

      **Then “Sign-in” to Markbot.**

  - title: "Final checklist"
    before: |
      Double check you’ve installed everything on your computer.

      *Here’s a checklist to help out:*
    tasks:
      - "Configure Finder"
      - "Configure keyboard preferences"
      - "The Unarchiver"
      - "Firefox"
      - "Chrome"
      - "Opera"
      - "Configure Safari"
      # - "Create a BrowserStack account"
      - "Get HTML files to open properly"
      - "Create a GitHub account"
      - "GitHub Desktop"
      - "Command Line Tools"
      - "Java Developer Kit"
      - "Markbot"
---
