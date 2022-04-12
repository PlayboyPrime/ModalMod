# CONFIG EXPLANATION
***

## submit

![image](https://user-images.githubusercontent.com/55946112/163048665-d46a5460-3b82-4b2e-9971-efcb47efa632.png)


This category contains options that will happen after a modal has been submitted.

Variables you can use in sendMessage.channelId:

|Variable|Replacement|
|--------|-----------|
|{user.dm}|Will send the message to the user.|


Variables you can use in replyToinIeraction.message and sendMessage.message:

|Variable|Replacement|
|--------|-----------|
|{user.id}|Will be replaced with the user id.|
|{user.name}|WIll be replaced with the user name.|
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


## replyToinIeraction

![image](https://user-images.githubusercontent.com/55946112/163046736-352649ec-9b22-4c5e-9316-0e70d0d59974.png)
 

If replyToinIeraction.message is not empty, the bot will send a reply to the submit interaction.

ephemeral: If true, only the Modal author can see the reply.

message: This string will be sent as a reply to the submit interaction.


## sendMessage 

![image](https://user-images.githubusercontent.com/55946112/162878468-1cb60ea1-f026-48c0-a1c3-a77eb122b014.png)


If sendMessage.channelId and sendMessage.message is not empty, the bot will send a message to a channel.

channelId: This will be the channelId or {user.dm} where the message will be sent. Leave this blank for no message.

message: This will be the message content. Leave this blank for no message.

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

Style: short or long. short is a one-line input box. long has 3 lines and more space to write.

MinLength: 0 to 4000. this will be the amount of characters the user has to write in this input before it can be submited.

MaxLength: 1 to 4000. This will be the maximum of characters the user can write in this input.

Placeholder: This will be the placeholder of the input.

Required: If this is true the user has to write something in this input before it can be submited.
