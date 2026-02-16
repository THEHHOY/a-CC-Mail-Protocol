# a-CC-Mail-Protocol
I need a mail protocol for my CC rp server so I design it here

# The design of the protocol

Port is 6060

## Sending Mail
```lua
{
  ["PROTOCOL"] = "mail",
  ["Subject"] = SUBJECT,
  ["Message"] = MESSAGE,
  ["Attachments"] {
    ["filename"] = FILEDATA
  } -- Optional
  ["Receipient"] = THE_MAIL_OF_THE_RECEIPIENT, -- Can be "JOE"
  ["Hostname"] = THE_NAME_OF_HOST, -- Can be "example.com"
}
```
