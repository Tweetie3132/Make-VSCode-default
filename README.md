# Set VSCode as the default editor for most programming languages. (macOS)

## Tired of accidentally opening Xcode on your Mac?

Me too. So here's a script that fixes that for ya. 👍👍👍👍
\
\
(It basically makes Visual Studio Code the default editor for most programming languages, except for Objective-C and Swift, [which are optional](#include))
 ## How to install:

1.	Install Homebrew if you haven’t:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" 
```
2.	Install duti:
```
brew install duti
```
3.	Find VSCode’s bundle ID (optional - Do this if the code doesn’t work):
```
osascript -e 'id of app "Visual Studio Code"'
```
You’ll get something like: 
`com.microsoft.VSCode`
* **Note: If you have something else, replace it with the ID I used in my code. Otherwise, do nothing.**

4. Run the script:
```
sh script.sh
```

<h2 id="include">Include Objective-C and Swift (optional):</h2>
Simply remove the <code>#</code> at the start of the last two lines in the script.
<br><br><br><br><br>
