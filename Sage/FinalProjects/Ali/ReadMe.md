# Skill Description
{
    "interactionModel": {
        "languageModel": {
            "invocationName": "alis valuable facts",
            "intents": [
                {
                    "name": "AMAZON.FallbackIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.CancelIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.HelpIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.StopIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.NavigateHomeIntent",
                    "samples": []
                },
                {
                    "name": "RPSIntent",
                    "slots": [
                        {
                            "name": "myChoice",
                            "type": "AMAZON.Color"
                        }
                    ],
                    "samples": [
                        "my choice is {myChoice}"
                    ]
                }
            ],
            "types": [
                {
                    "name": "Team",
                    "values": [
                        {
                            "name": {
                                "value": "Raptors"
                            }
                        },
                        {
                            "name": {
                                "value": "Warriors"
                            }
                        }
                    ]
                }
            ]
        }
    }
}
