
# WhatsApp Button Embed Script

This JavaScript script allows you to easily embed a WhatsApp button on any website. Users can integrate this script into their websites to provide a convenient way for their visitors to initiate a WhatsApp conversation with a predefined phone number and message.


## How to Use


### Step 1: Include the Script


Include the `script.js` file in your HTML file, just before the closing `</body>` tag:


```html
<script src="./script.js"></script>

```

### Step 2: Create the WhatsApp Button

Call the talhag3WAButton function to create the WhatsApp button. You can customize the button's behavior by passing optional parameters:

```html
<script>talhag3WAButton(showWpBtn, phone, text);</script>
```

`showWpBtn (optional): A boolean value that determines whether to display the WhatsApp button. Set it to true to show the button or false to hide it initially.

phone (optional): The phone number to which the WhatsApp message will be sent. Provide it as a string, including the country code and without spaces or special characters (e.g., '923134711699').

text (optional): The default message that will be pre-filled in the WhatsApp chat. You can customize this message (e.g., 'Hi, Talha').


# Example 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- ... -->
</head>
<body>
    <!-- Include the script.js file -->
    <script src="./script.js"></script>

    <!-- Call the talhag3WAButton function to create the WhatsApp button -->
    <script>talhag3WAButton(true, '923134711699', 'Hi, Talha')</script>
</body>
</html>
```

