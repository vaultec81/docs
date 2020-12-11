# workflows

Configure your workflows

## `mailscript workflows:add`

add a workflow

```
USAGE
  $ mailscript workflows:add

OPTIONS
  -a, --action=action                id of the action accessory
  -f, --forward=forward              email address for forward action
  -h, --help                         show CLI help
  -h, --html=html                    html of the email
  -r, --reply                        email address for reply action
  -s, --subject=subject              subject of the email
  -t, --name=name                    (required) name of the workflow
  -t, --text=text                    text of the email
  -t, --trigger=trigger              (required) id of the trigger accessory
  -w, --webhook=webhook              url of the webhook to call
  --alias=alias                      email address for alias action
  --body=body                        file to take webhook body from
  --domain=domain                    constrain trigger to emails are from an email address with the given domain
  --from=from                        constrain trigger to emails from the specified address
  --hasattachments                   constrain trigger to emails with attachments
  --hasthewords=hasthewords          constrain trigger to emails that have the words specified
  --headers=headers                  file to take webhook headers from
  --method=(PUT|POST|GET)            [default: POST] HTTP method to use in webhook
  --noninteractive                   do not ask for user input
  --replyall                         email address for reply all action
  --seconds=seconds                  period of time to calculate the trigger over
  --send=send                        email address for send action
  --sentto=sentto                    constrain trigger to emails sent to the specified address
  --subjectcontains=subjectcontains  constrain trigger to emails whose subject contains the specified text
  --times=times                      number of emails in a period for trigger to activate
  --workflow=workflow                id of the workflow to be acted on
```

## `mailscript workflows:delete`

delete a workflow

```
USAGE
  $ mailscript workflows:delete

OPTIONS
  -h, --help               show CLI help
  -w, --workflow=workflow  (required) id of the workflow to be acted on
```

## `mailscript workflows:list`

list the workflows

```
USAGE
  $ mailscript workflows:list

OPTIONS
  -h, --help  show CLI help
```
