---
layout: page
title: Install Jekyll on Mac
description: Jekyll is a static site generator that helps create and manage websites without a database or server-side scripting
img: assets/img/jekyll.jpg
importance: 1
category: install
---

You must have Ruby and RubyGems installed on your system to install Jekyll. Here are the steps to install Jekyll on a Mac system:

1. Install Ruby:

    Although macOS comes with Ruby pre-installed, it's usually an older version. Jekyll requires Ruby 2.5.0 or higher. 
    To install the latest version of Ruby, use the following command:

    ```
    sudo apt-get install ruby-full
    ```
    Once the installation is complete, add the following line to your `~/.zshrc` or `~/.bashrc` file:

    ```
    if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi
    ```
    Save the file and restart the Terminal. Now, install the latest Ruby version:

    ```
    rbenv install 3.0.2
    rbenv global 3.0.2
    ```

    Verify the Ruby version with:

    ```
    ruby -v
    ```
2. Install Jekyll and Bundler:

    Now that you have the latest Ruby version installed, you can install Jekyll and Bundler using the following command:

    ```
    gem install jekyll bundler
    ```

4. Verify the Jekyll installation:

    To ensure Jekyll has been installed correctly, run the following command:

    ```
    jekyll -v
    ```
    If the installation was successful, you should see the Jekyll version number.

5. Create a new Jekyll site:

    To create a new Jekyll site, use the following command (replace `my-new-site` with your desired directory name):

    ```
    jekyll new my-new-site
    ```

6. Change to the new site's directory:

    ```
    cd my-new-site
    ```

7. Start the Jekyll development server:

    ```
    bundle exec jekyll serve
    ```
Now, open your web browser and navigate to `http://localhost:4000` to see your Jekyll site live.

That's it!