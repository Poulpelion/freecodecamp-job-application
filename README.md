# freecodecamp-job-application

Free code camp lab Job application form.

I'll try to produce a website, just by copying the example.

First without checking the "user stories" which gives away too many hint.

Features I can see in the example:

• Body has a white background

• The whole form is inside a container with white background, no border but box-shadow

• there's more padding on side of the body than top and bottom

• all the content is center-aligned except labels and fieldset's legend which are left-aligned (it would be interesting to find out if/how I can change the legend position)

There are :
• 1 input type="text" for the name with placeholder, required

• 1 input type="email" with placeholder, required

• select dropdown menu with 3 options plus a non valid option (no value) which acts as placeholder

• 1 fieldset with
    • radio buttons and their labels on the right side

• 1 textarea with placeholder, required

• 1 submit button

    ----------

• all inputs, select and textarea have labels 

• The inputs, fieldset and button elements take up most of the width of the container (except input type="radio")

• when not valid or not compiled inputs borders are red

• when compiled with valid content, inputs border turn green

• when focused no style except select and submit, which have default blue outline 

• radio buttons look larger than usual, turn green when selected label turns green too (I need to check I will have to nest input into label -> implicit label)

• submit button as green background and text is white

• submit button:hover :active background dark blue

• when clicking submit message for unvalid or not compiled input, probably default behavior

• nothing happen when all valid 
