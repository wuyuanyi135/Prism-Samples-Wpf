pack all command in one class (ApplicationCommands) and pass it to the container so that all modules will share the command set.
composite command can be used to register multiple delegate command and fulfill their canexecute condition. so composite command should be passed along
