# CONFIG EXPLANATION


submit

replyToinIeraction

![image](https://user-images.githubusercontent.com/55946112/162878422-151491f4-dbe2-4121-a856-b443ecbf52a8.png)
 



If replyToinIeraction.message is not empty, the bot will send a reply to the submit interaction.

ephemeral: If true, only the Modal author can see the reply.

message: This string will be sent in the interaction channel as a reply to the submit interaction.


sendMessage 

![image](https://user-images.githubusercontent.com/55946112/162878468-1cb60ea1-f026-48c0-a1c3-a77eb122b014.png)




If sendMessage.channelId and sendMessage.message is not empty, the bot will send a message to a channel.

channelId: This will be the channelId where the message will be sent. Leave this blank for no message.

message: This will be the message content. Leave this blank for no message.


interactionCustomId: If a button interaction is triggerd with this customId, then this modal will be shown. 

![image](https://user-images.githubusercontent.com/55946112/162879082-946cca4b-6de2-47c0-95f7-980b3223c2ea.png)




Title: This will be the Modal Title.

CustomId: This will be the customId for the Modal. You can set this to anything.


addComponents You can add here up to 5 TextInputComponents. Make sure you name them upcounting (TextInputComponent1, TextInputComponent2 etc) 

![image](https://user-images.githubusercontent.com/55946112/162878556-df20d151-051a-49ae-b671-1ba87aa3a477.png)




TextInputComponent


CustomId: This will be the customId for the TextInputComponent. You can set this to anything.

Label: This will be the Label for the TextInputComponent.

Style: short or long. short is a one-line input box. long has 3 lines and more space to write.

MinLength: 0 to 4000. this will be the amount of characters the user has to write in this input before it can be submited.

MaxLength: 1-4000. This will be the maximum of characters the user can write in this input.

Placeholder: This will be the placeholder of the input.

Required: If this is true the user has to write something in this field before it can be submited.
