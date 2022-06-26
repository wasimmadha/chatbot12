# Kira Bot

#### Intelligent virtual assitant to solve duplicate queries

**Data used** -- Skype Chat data 

Command line application works in a form of Question and answer

## License
This project is licensed under the MIT License - see the license file for details

### USE

<code>rasa shell</code> for the command line. 

#### API deployed on Google Azure cloud
**Use using API:**
Post request on http://104.211.231.131:5005/webhooks/rest/webhook with parameter "message" in json format
E.g.
{"message": "I have a career gap"}

Response e.g.:
[
    {
        "recipient_id": "default",
        "text": "You can raise a demand from the dashboard"
    }
]
