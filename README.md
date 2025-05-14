# blogMemeGenerator

a service which lets you insert memes into your blog

plan:

1. go to google ai api, follow instructions and integrate the google AI API
2. use a crawler to get the html data from a given url. feed this data to the LLM
3. create a prompt.
4. feed the html blog and the prompt to the LLM. Get the response array.
5. use the response array data(various parameters) to fetch and match the suitable meme template data from the vector DB.
6.
