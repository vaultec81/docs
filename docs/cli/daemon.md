# daemon

Run scripts within a local daemon in response to emails recieved in Mailscript.

## `mailscript daemon`

Run a daemon to execute scripts on email arrival

```
USAGE
  $ mailscript daemon

OPTIONS
  -h, --help             show CLI help

  --accessory=accessory  (required) the accessory to listen in on

  --command=command      (required) The shell command to run on message received
```