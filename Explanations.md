# CONFIG EXPLANATION
***

## submit

![image](https://user-images.githubusercontent.com/55946112/163278941-cd15e2a2-edca-4b9d-82af-5293fe86de98.png)


This category contains options that will happen after a modal has been submitted.

## Variables you can use in sendMessage.channelId and sendEmbed.channelId:

|Variable|Replacement|
|--------|-----------|
|{user.dm}|Will send the message to the user.|
|{submit.channel}|Will send the message to channel where the modal was submitted.|


## Variables you can use in replyToInteraction.message, sendMessage.message and sendEmbed(title, author and description):

|Variable|Replacement|
|--------|-----------|
|{user.id}|Will be replaced with the user id.|
|{user.name}|Will be replaced with the user name.|
|{user.discriminator}|Will be replaced with the users discriminator.|
|{user.avatar_url}|Will be replaced with the users avater url.|
|{input}|Will be replaced with all of the inputs with the input name togheter.|
|{input.a}|Will be replaced with the first input.|
|{input.b}|Will be replaced with the second input.|
|{input.c}|Will be replaced with the third input.|
|{input.d}|Will be replaced with the fourth input.|
|{input.e}|Will be replaced with the fifth input.|
|{guild.name}|Will be replaced with the guild name.|
|{guild.id}|Will be replaced with the guild id.|
|{guild.member_count}|Will be replaced with the guild member count.|


## replyToInteraction

![image](https://user-images.githubusercontent.com/55946112/163071718-093cbc50-4c29-4a75-a8ec-2dc4ff62932b.png)
 

If replyToInteraction.message is not empty, the bot will send a reply to the submit interaction.

ephemeral: ```true or false``` If true, only the Modal author can see the reply.

message: This string will be sent as a reply to the submit interaction. Leave this empty if you want no reply.


## sendMessage 

![image](https://user-images.githubusercontent.com/55946112/163281823-189605c2-eb4c-4030-b7ea-3f69e65e9d22.png)


If sendMessage.channelId and sendMessage.message is not empty, the bot will send a message to a channel.

channelId: This will be the channelId or {user.dm} where the message will be sent. Leave this empty for no message.

message: This will be the message content. Leave this empty for no message.

reactions: ```unicode or emoji id``` ```Seperate with comma.``` The bot will react to this message with these emojis. 


## sendEmbed

![image](https://user-images.githubusercontent.com/55946112/163279005-e8e9dbc3-b03d-44c9-a95e-e0dcaeaa9baf.png)


If sendEmbed.channelId is not empty, the bot will send an embed to a channel.

channelId: This will be the channelId or {user.dm} or {submit.channel} where the message will be sent. Leave this empty for no message.

Everything else should be self explanatory.


***
## Modal properties
![image](https://user-images.githubusercontent.com/55946112/162880475-9281be9b-2a9a-4e09-888f-3be80620a989.png)



interactionCustomId: If a button interaction is triggerd with this customId, then this modal will be shown. 

Title: This will be the Modal Title.

CustomId: This will be the customId for the Modal. You can set this to anything.


## addComponents

![image](https://user-images.githubusercontent.com/55946112/163047069-4cdb5297-2db4-452e-83a7-6b4d59766e36.png)


You can add here up to 5 TextInputComponents. Make sure you name them upcounting (TextInputComponent1, TextInputComponent2 and so on) 

## TextInputComponent


CustomId: This will be the customId for the TextInputComponent. You can set this to anything.

Label: This will be the Label for the TextInputComponent.

Style: ```short or long``` Short is a one-line input. Long has 3 lines and more space to write.

MinLength: ```0 to 4000``` This will be the amount of characters the user has to type in this input before it can be submited.

MaxLength: ```1 to 4000``` This will be the maximum of characters the user can type in this input.

Placeholder: This will be the placeholder of the input. Leave empty for no placeholder.

Required: ```true or false``` If this is true the user has to write something in this input before it can be submited.
