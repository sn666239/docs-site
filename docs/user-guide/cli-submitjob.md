# DRAFT - Submitting Zowe CLI commands

                        ***UNDER CONSTRUCTION***

## Understanding the anatomy of command line syntax

Zowe CLI is a command line interface (CLI) that uses options and arguments to provide specific instructions that tell a computer to do something, such as execute (run) an application. Command line syntax is comprised of the following components:

- **Argument:** An argument is a file name, application name, or other type of data that you specify in a command in order for the command to use it as input. Arguments are pieces of information that tell a command what to do and where to send the results.

- **Positional argument:** A set of arguments that are passed to a command in a required or logical order of operation.

- **Keyword argument:** A positional argument that contains a default value.

- **Key value argument:** A (key, value) argument is an argument where the key describes the value.

- **Option:** An option is a type of argument that defines how a command should behave. An option, sometimes referred to as a flag or a switch, is a single-letter or full word that modifies the way a command behaves in a predetermined manner. You precede options using a hyphen or a minus sign ( - ).

- **Flag:** A flag is a stand-alone key. Its presence (or absence) provides information to an application. Flags are usually described as a boolean value.

- **Switch:** A switch is an option that modifies the behavior (properties) of a command.

## Assembling Zowe CLI command syntax 

Zowe CLI commands are organized by command groups. The command groups focus on specific business processes. For example, the Zowe zos-tso commands group lets you issue TSO commands and interact with TSO address spaces.

