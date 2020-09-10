# CommandEvent

## import
`import crafttweaker.event.CommandEvent;`

## Extended from
[IEventCancelable](/CraftTweaker/Vanilla/Events/IEventCancelable.md)

## .commandSender
> Gets the command sender.
>
> **Type:** Getter  
> **Returns:** [ICommandSender](/CraftTweaker/Vanilla/Command/ICommandSender.md)

## .command
> Gets the command.
>
> **Type:** Getter
> **Returns:** [ICommand](/CraftTweaker/Vanilla/Command/ICommand.md)

## .parameters
> Gets/Sets the parameters set in the command sent.
>
> **Type:** Getter/Setter
> **Returns:** [string](/CraftTweaker/Vanilla/Base-Types/string.md)[]

# By proxy methods

## IEventCancelable
> | Getter/Method   | Setter/Method     | Type                  |
> |-----------------|-------------------|-----------------------|
> | canceled        | canceled          | [bool](/CraftTweaker/Vanilla/Base-Types/bool.md)                  |
> | cencel()        |                   | [void](/CraftTweaker/Vanilla/Base-Types/void.md)                  |