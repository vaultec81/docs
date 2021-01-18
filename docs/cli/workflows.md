# workflows

Configure your workflows

## `mailscript workflows:add`

add a workflow

```
USAGE
  $ mailscript workflows:add

OPTIONS
  -o, --input=input      (required) name of the input to listen in for incoming emails
  -t, --trigger=trigger  (required) name of the trigger to be used
  -a, --action=action    (required) name of the action to be executed
  -n, --name=name        (required) name of the workflow
```

## `mailscript workflows:delete`

delete a workflow

```
USAGE
  $ mailscript workflows:delete

OPTIONS
  -w, --workflow=workflow  (required) id of the workflow to be acted on
```

## `mailscript workflows:list`

list the workflows

```
USAGE
  $ mailscript workflows:list
```
