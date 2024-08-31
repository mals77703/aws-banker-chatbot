#  Build a Chatbot using AWS
In this project, you built a sophisticated banking chatbot using Amazon Lex, focusing on providing a seamless user experience. You started by configuring a basic intent and creating diverse utterances, enabling the bot to recognize various user phrases. To handle unrecognized inputs gracefully, you edited the FallbackIntent and added varied responses for a more natural interaction.

You rigorously tested the bot in both text and voice formats and set up a custom slot type for recognizing different bank account types. By linking these slots to the relevant intent and integrating a Lambda function, you enhanced the bot’s capabilities and accuracy. You also implemented code hooks and saved user information, such as birthdays, to streamline follow-up queries.

To improve user experience further, you created a FollowupCheckBalance intent with context carryover and added a confirmation prompt for secure transactions. Finally, you automated the chatbot’s deployment using AWS CloudFormation, ensuring all resources were correctly configured.
