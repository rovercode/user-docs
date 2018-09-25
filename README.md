# user-docs
User documentation for rovercode. https://docs.rovercode.com

## Building the website locally

[Hugo](https://gohugo.io/) is the static site-building used to turn the Markdown content in this repo into HTML webpages.
Hugo is similar to tools like Jekyll that Github Pages uses.
These instructions explain how to intall Hugo and use it to build and view the rovercode documentation website.

* Clone this repository: `git clone https://github.com/rovercode/user-docs.git`

* Install Hugo using [these instructions](https://gohugo.io/getting-started/installing/). Note that there are more detailed instrutions for each operating system if you scroll down past the Quick Install section.

* Open a command prompt in this directory. Run the command `hugo serve`.

* You will see a lot of messages. Toward the bottom, look for one sorta like this: `Web Server is available at http://localhost:1313/ (bind address 127.0.0.1).` Copy-pase the `http://localhost:1313` into the address bar of your web browser and hit enter. You should see the website!

* As you save changes to the files, the site will automatically rebuild and the page will refresh in your browser.
