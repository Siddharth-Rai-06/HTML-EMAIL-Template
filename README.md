
# HTML-EMAIL-Template


This project showcases a template that renders embedded HTML code inside email clients.
Writing E-mail HTML code requires a little differenta pprocah than writing a simple code.
There are certain rules needed to follow to make your code all email client compatible and make it render inside your email.



## Rules

- It is required to write your CSS code inline rather than in internal or extenral. Some of it can be internal.
- We are also required to upload all the images used, on the web, rather than using them locally on your device and linking it to your code.
- We need to write some conditional statements to render your code for MS Outlook.
- Always use table tags and its sub tags instead of using divs.
- Always use hex code for colors rather than text so that email clients can render them better. 
- Use “display:block;” and it will remove the extra spacing.
- Don't use a shorthand declaration. For example, “margin-top: 5px” may work where “margin: 5px 0 0 0;” 
- If you’re having trouble getting your table cells to stack in mobile display, the quick fix is to change your <td> tags to <th> tags.
- It is always better to avoid an all-image email.
- Include ARIA markup by writing role:"presentation " in the table tags
- Try to achieve an email that maintains branding and accessibility on all email clients, rather than focusing on small rendering details.


## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Body background | ![#F8F9FA](https://via.placeholder.com/10/f8f9fa?text=+) #F8F9FA |
| Result Button | ![#043CD0](https://via.placeholder.com/10/043CD0?text=+) #043CD0 |
| High Severity | ![#FF0000](https://via.placeholder.com/10/FF0000?text=+) #FF0000 |
| Sub-header Text  | ![#666666](https://via.placeholder.com/10/666666?text=+) #666666 |
| Borders Color | ![#EFF1F4](https://via.placeholder.com/10/EFF1F4?text=+) #EFF1F4 |
| Banner color 1| ![#043CD0, #03298E](https://via.placeholder.com/10/043CD0?text=+)#043CD0 |
| Banner color 2 | ![#03298E](https://via.placeholder.com/10/03298E?text=+) #03298E |
| Account Info Background  | ![#EEEEEE](https://via.placeholder.com/10/EEEEEE?text=+) #EEEEEE |

