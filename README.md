# Quote editor
A simple quote editor made in rails 7 with turbo. 




## Run Locally

Clone the project

```bash
  git clone https://github.com/D-Forz/rails-quote-editor.git
```

Go to the project directory

```bash
  cd rails-quote-editor
```

Install dependencies

```bash
  setup
```

Start the server

```bash
  dev
```


## Running Tests

To run tests, run the following command

```bash
  rails test:system
```
 If you are getting a Webdrivers::BrowserNotFound: Failed to find Chrome binary error, you need to install the latest version of Chrome:


```bash
  # macOS
brew install --cask google-chrome

# Ubuntu
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
rm -rf google-chrome-stable_current_amd64.deb
## Appendix

Any additional information goes here

