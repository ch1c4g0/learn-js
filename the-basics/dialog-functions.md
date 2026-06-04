

<p><h1>The main objective</h1></p>

<p>One of the main objectives of Java Script is to provide dialogue boxes for interaction with users and dynamically update content on web pages.</p>

<p>Java Script has built-in functions like, alert, prompt, and confirm.</p>

<p>These functions allow developers to display messages, gather input, and obtain user confirmation. If these features are not implemented securely, attackers may exploit them.</p>

<p><h2>Alert</h2></p>

<p>Displays a message in a dialogue box with an "OK" button, typically used to convey warnings to users/alerts to users.</p>

```
alert("Hello GitHub")
```

<p><h2>Prompt</h2></p>

<p>Displays a dialogue box that asks the user for input, the value entered is returned when the user clicks "OK"</p>

<p>If a user were to click cancel, the input would not be displayed</p>

```
prompt("What is your name? ")
'CH1C4G0'
```
```
name = prompt("What is your name?");
    alert("Hello! ", name);

(return value)

What is your name? Dingo

Hello! Dino
```

<p><h2>Confirm</h2></p>

<p>Displays a dialogue box with a message and two buttons, "OK", and "Cancel". It returns boolean expressions, OK = True, Cancel = False</p>

```
confirm("Are you sure?");

(return value)
______________________________________
chrome://new-tab-page-third-party-says
Are you sure?
                    Cancel     OK
--------------------------------------
#True or false is then returned on the back-end.
```


