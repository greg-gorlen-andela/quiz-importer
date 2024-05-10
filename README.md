# quiz-importer

This tool imports unstructured input to a Qualified quiz. It uses OpenAI to convert the input to Qualified's quiz format, so inaccuracies can occur. Be sure to check the results and use at your own risk.

[Try it](https://greg-gorlen-andela.github.io/quiz-importer/)

### TODO

- Stream JSON as it's created by OpenAI
- Allow appending to an existing quiz
- Add more meta fields like difficulty
- set query params on submit
- handle color mode changes
- Break import into 2 steps and make json contenteditable
- use Andela styling
- could also accept chatGPT conversation URL as input
- could offer a userscript-created button in ChatGPT to pop open a new tab to run the request via query params
- alternate approach: run the backend on another server/localhost and have the button in ChatGPT send the request there to handle the API calls
