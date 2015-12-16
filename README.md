# ChainOfResponsibility
Demonstrate ChainOfResponsibility, Command and Observer Patterns

# To Run
- Main

#Description
EmailClient will create a Processor. In this Processor a number of Handlers will be added. Each of these handlers will
be executed in sequence. If the request match the responsibillity of the handler, a command will be performed within that handler.

# Gratitude
Based on examples from https://dzone.com/articles/design-patterns-uncovered-chain-of-responsibility
