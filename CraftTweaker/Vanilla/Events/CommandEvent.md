# CommandEvent

## import
`import crafttweaker.event.CommandEvent;`

## Extended from
IEventCancelable

## .commandSender
> Gets the command sender.
>
> **Type:** Getter  
> **Returns:** ICommandSender

## .command
> Gets the command.
>
> **Type:** Getter
> **Returns:** ICommand

## .parameters
> Gets/Sets the parameters set in the command sent.
>
> **Type:** Getter/Setter
> **Returns:** string[]

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | bool                  |
> | cencel()        |                   | void                  |