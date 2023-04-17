---
layout: page
title: Install Ruby on Mac
description: Ruby is a versatile programming language used for web development, automation, and data processing
img: assets/img/ruby.jpg
importance: 2
category: install
---

Here are the steps to install Ruby on a MacOS:

1. Open Terminal. You can do this by pressing the Command + Spacebar keys to open Spotlight, then typing "Terminal" and hitting Enter.

2. Install Homebrew, a popular package manager for macOS, by running the following command in Terminal:

    ```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/
install/HEAD/install.sh)"
    ```

3. Once Homebrew is installed, run this command to update it:

    ```
brew update
    ```

4. Verify that Ruby has been installed by checking the version:

    ```
ruby -v
    ```

    You should see a message similar to:

    ````
    ruby 2.7.4p191 (2021-07-07 revision a21a3b7d23) [arm64-darwin20]
    ````

That's it! Ruby should now be installed on your Mac.

> Note: If you have any issues during this process, you may need to run the commands with **`sudo`** or check the [Homebrew documentation](https://docs.brew.sh/) for troubleshooting steps.