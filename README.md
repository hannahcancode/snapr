## Snapr - Social photo messaging from the terminal

[![Build Status](https://travis-ci.org/peterept/snapr.svg?branch=master)](https://travis-ci.org/peterept/snapr)

Snap and send a selfie directly from the terminal to everyone watching in your network.

![Imgur](http://i.imgur.com/sa9GvzPm.png)

To download this application use:

   ```
   git clone https://github.com/peterept/snapr.git
   ```

# Installation

1. Open the terminal.
2. Install Image Magick (version 6 required)
   What version do you have? run `convert --version`

    ```
    brew install imagemagick@6
    ```

    ```
    brew link --force imagemagick@6
    ```
3. Install RMagick gem

    ```
    gem install rmagick    
    ```
3. Install Catpix gem

    ```
    gem install catpix    
    ```
4. Install Lolcommits gem

    ```
    gem install lolcommits    
    ```

# Instructions

For help, use:
    ```
    ruby snapr.rb 
    ```

To watch for chat images, use:
    ```
    ruby snapr.rb -watch    
    ```

To take and send a chat image, use:
    ```
    ruby snapr.rb "Hello everyone"    
    ```

