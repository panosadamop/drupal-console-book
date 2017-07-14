# chain
साखळी आदेशाची अंमलबजावणी करावी.

**application.gitbook.messages.usage:**
```
drupal chain [arguments] [options]
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | आदेश समाविष्ट असलेल्या वापरकर्ता परिभाषित फाइलची अंमलबजावणी.
--placeholder | commands.chain.options.placeholder
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--debug | application.options.debug
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
command | The command to execute

## application.gitbook.messages.examples
* पूर्ण पथ वापरून फाइल पर्याय प्रदान करणे.
```
drupal chain \
  --file="/path/to/file/chain-file.yml"
```