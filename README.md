# HTML Email Templates: basic info

## Table of Contents

- [Common Tips](#common-tips)
    - [Fonts](#fonts)
    - [Images](#images)
    - [Other Tips](#other-tips)
- [Static Frameworks](#static-frameworks)
- [Basic Template](#basic-template)
- [Responsive Emails](#responsive-emails)
- [Inliners](#inliners)
- [Tools for Testing](#tools-for-testing)
- [Grunt/Gulp](#grunt-gulp)

![Actual Clients](http://frontender.com.ua/email_templates/clients.png  "Actual Clients")

## Common Tips

### Read First

- [Верстка email рассылок от А до Я для чайников](https://habrahabr.ru/post/252279/)
- [Сумбурно о разработке писем](https://habrahabr.ru/post/267499/)
- [The Ultimate Guide to CSS (поддержка CSS свойств клиентами)](https://www.campaignmonitor.com/css/)

### Images

- Don't use background-images.
- Use fallbacks for &lt;img&gt; (bgcolor, alt). By default, some email clients hide images.

### Fonts

- **Don’t Use Custom Fonts Stacks**. 
- **Safe Web Fonts**: 
    - Sans Serif: Arial, Arial Black, Tahoma, Trebuchet MS, Verdana 
    - Serif: Courier, Courier New, Georgia, Times, Times New Roman
- ![Web Fonts Support](http://frontender.com.ua/email_templates/fonts.png  "Web Fonts Support")
- **Links to read:**
  - [Типографика в дизайне email-писем](https://habrahabr.ru/company/pechkin/blog/259909/)
  - [templates.mailchimp.com/design/typography](http://templates.mailchimp.com/design/typography/)
  - [campaignmonitor.com/dev-resources/will-it-work/webfonts](https://www.campaignmonitor.com/dev-resources/will-it-work/webfonts/)

### Other Tips
- [Don't use forms](https://habrahabr.ru/company/pechkin/blog/268927/)
- [A Guide to Bulletproof Buttons in Email Design](https://litmus.com/blog/a-guide-to-bulletproof-buttons-in-email-design)
- [Номера телефонов в почтовых клиентах](https://habrahabr.ru/post/269045/)

## Static Email Frameworks

- [Foundation for Emails 2 (Formerly Ink)](http://foundation.zurb.com/emails.html)
- [emailframe.work](http://emailframe.work)
- [Cerberus](http://tedgoas.github.io/Cerberus/)
- [The HTML Email Boilerplate](https://paulund.co.uk/html-email-boilerplate)


## Basic Template
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
   <html>
   <head>
   
   	<title>Email Framework</title>
   	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0" />
   	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
       <!--[if !mso]>
       <meta http-equiv="X-UA-Compatible" content="IE=edge" />
       <!--<![endif]-->
       
       <!-- Demo Only -->
       <link rel="stylesheet" href="mail.css" type="text/css" />
       
       <style type="text/css">
       
           /* Paste CSS */
       
       </style>
       
   	<!--[if gte mso 15]>
   	<style type="text/css">
   		table { font-size:1px; line-height:0; mso-margin-top-alt:1px;mso-line-height-rule: exactly; }
   		* { mso-line-height-rule: exactly; }
   	</style>
   	<![endif]-->    
   
   </head>
   <body marginwidth="0" marginheight="0" leftmargin="0" topmargin="0" style="background-color:#F6F6F6;  font-family:Arial,serif; margin:0; padding:0; min-width: 100%; -webkit-text-size-adjust:none; -ms-text-size-adjust:none;">
   
   	<!--[if !mso]><!-- -->
   	<img style="min-width:640px; display:block; margin:0; padding:0" class="mobileOff" width="640" height="1" src="images/spacer.gif">
   	<!--<![endif]-->
   
       <!-- Start Background -->
       <table width="100%" cellpadding="0" cellspacing="0" border="0" bgcolor="#F6F6F6">
           <tr>
               <td width="100%" valign="top" align="center">
         
                   <!-- Let's Go! -->
         
               </td>
           </tr>
       </table>
       <!-- End Background -->
       
   </body>
   </html>
```

## Tools for Testing
- [https://putsmail.com/tests/new](https://putsmail.com/tests/new)
- [MailList Controller for Windows](https://www.arclab.com/en/amlc/)

## Inliners

- [Mailchimp CSS Inliner Tool](http://templates.mailchimp.com/resources/inline-css/)
- [Foundation for Emails Inliner](http://foundation.zurb.com/emails/inliner.html)
- [Campaign Monitor CSS Inliner](https://inliner.cm/)
- [PutsMail CSS Inliner](https://putsmail.com/inliner)

## Responsive Emails

- [Responsive Email Resources](http://responsiveemailresources.com/)
- [Responsive Email Patterns](http://responsiveemailpatterns.com/)

## Grunt/Gulp

- [Simple Email Development Framework](https://github.com/dudeonthehorse/kilogram)
- [grunt-email-builder](https://github.com/Email-builder/grunt-email-builder)
- [Gulp-Email-Creator](https://github.com/darylldoyle/Gulp-Email-Creator)
- [A workflow for responsive emails using Ink and Grunt](https://medium.com/@victorgarcia/a-workflow-for-responsive-emails-using-ink-and-grunt-32d607879082)
- [A Gulp Workflow for Building HTML Email](https://bitsofco.de/a-gulp-workflow-for-building-html-email/)

## Author

**Alex Smoll**

## License

[CC0 License](LICENSE)

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")
