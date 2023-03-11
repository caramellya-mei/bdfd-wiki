# $onlyForUsers
The command can only be executed by users with certain 'usernames'.

## Usage
```
$onlyForUsers[usernames;...;errorMessage]
```

### Parameters 
- `usernames` `(Type: String || Flag: Emptiable)`: The names of the users that can execute this command. Separate the usernames using `;`.
- `errorMessage` `(Type: String || Flag: Emptiable)`: The message that is returned when the command is used by a non-whitelisted user.