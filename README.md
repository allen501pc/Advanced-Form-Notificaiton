# Advanced-Form-Notificaiton
This application extend from Google developer tutorial named "[Quickstart: Add-on for Google Forms](https://developers.google.com/apps-script/quickstart/forms-add-on)".

I modified the **Notification email body** of **Notify respondents**. 

For example, your form may be like this format (_field title_ and _field type_):

	email: [text]
	name:[text]

and you want to customize your notification content for each respondent's email like this ( in this case, the respondent's e-mail is allen501pc@gmail.com and his name is Allen:
    
    Thanks for filling our questionnaire survey. Your content shows below: 
    Your e-mail: allen501pc@gmail.com
    Your name: Allen

The easy way for you is just adding **Notification email body** of **Notify respondents** below:

    Thanks for filling our questionnaire survey. Your content shows below: 
    Your e-mail: __##email##__
    Your name: __##name##__

You can easily add the variables surronding with **__##** as prefix and **##__** as suffix. 

That's all. Enjoy it! 
