# Here are the modules you can copy paste into config.json

### Version 1.0.0

Dont forget rename it upcounting and add an comma!
---


## Modal

```json

"modal1": {

    "submit": {

        "replyToInteraction": {
            "ephemeral": "",
            "message": ""
        },

        "sendMessage": {
            "channelId": "",
            "message": ""
        }
    },

    "interactionCustomId": "",
    "Title": "",
    "CustomId": "",
    "addComponents": {

            
    }
}
```


## TextInputComponent

```json
"TextInputComponent1": {
    "CustomId": "",
    "Label": "",
    "Style": "",
    "MinLength": "",
    "MaxLength": "",
    "Placeholder": "",
    "Required": ""
}
```

## Modal with TextInputComponent

```json
"modal1": {

    "submit": {

        "replyToInteraction": {
            "ephemeral": "",
            "message": ""
        },

        "sendMessage": {
            "channelId": "",
            "message": ""
        }
    },

    "interactionCustomId": "",
    "Title": "",
    "CustomId": "",
    "addComponents": {

        "TextInputComponent1": {
            "CustomId": "",
            "Label": "",
            "Style": "",
            "MinLength": "",
            "MaxLength": "",
            "Placeholder": "",
            "Required": ""
        }
    }
}
```

## Config.json standard

```json
{
    "modal1": {

        "submit": {

            "replyToInteraction": {
                "ephemeral": "",
                "message": ""
            },

            "sendMessage": {
                "channelId": "",
                "message": ""
            }
        },

        "interactionCustomId": "",
        "Title": "",
        "CustomId": "",
        "addComponents": {

            "TextInputComponent1": {
                "CustomId": "",
                "Label": "",
                "Style": "",
                "MinLength": "",
                "MaxLength": "",
                "Placeholder": "",
                "Required": ""
            }
        }
    }
}
```
