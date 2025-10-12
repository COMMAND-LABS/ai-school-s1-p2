# TLDR

This workflow takes a list of news websites and has an LLM read each website to identify the top n articles. After the top n articles have been identified, they are reranked in a final step before a daily news report is sent via email.

## How to use

- You'll need to plug in an OpenAI API key to power the agent. Go over to the OpenAI platform linked below and purchase some credits. The minimum allowable purchase amount should be more than enough.
- Emails are delivered via the Gmail "Send a Message" node

## Related links & platforms

- https://platform.openai.com
- https://gmail.com/
