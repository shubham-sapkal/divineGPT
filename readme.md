
# DivineGPT

Introducing Divine-GPT, an impressive chatbot clone utilizing OpenAI's GPT-3.5 language model. 

Developed with Vue.js, vanilla JavaScript, and Node.js, this project showcases a cutting-edge conversational experience. Engage in natural language conversations with Divine-GPT to witness its remarkable understanding of context, informative responses, and human-like text generation. Whether seeking knowledge, assistance, or a friendly chat, Divine-GPT delivers an interactive and intelligent virtual companion. 

Experience the future of human-computer interaction at [insert project link], where Divine-GPT seamlessly bridges the gap between humans and AI, providing an engaging and immersive conversational platform for all users.





## Features of GroceryListApp


- Chatbot functionality: Divine-GPT serves as a chatbot, allowing users to engage in natural language conversations.
- OpenAI's GPT-3 language model: The project leverages the power of OpenAI's advanced language model to generate responses.
- Frontend development with Vue.js: The frontend of Divine-GPT is built using Vue.js, a popular JavaScript framework for creating interactive user interfaces.
- Vanilla JavaScript: In addition to Vue.js, vanilla JavaScript is utilized to enhance the project's functionality and user experience.
- Node.js for API calls: Node.js is employed to handle API calls and facilitate communication with the OpenAI API.
- Contextual understanding: Divine-GPT demonstrates an ability to understand and maintain context throughout conversations, enabling more coherent and meaningful interactions.
- Informative responses: The chatbot provides users with informative and relevant responses to their queries, serving as a valuable source of knowledge.
- Human-like text generation: The project showcases the language model's capability to generate human-like text, enhancing the authenticity of the conversational experience.
- Interactive virtual companion: Divine-GPT acts as an interactive and intelligent virtual companion, offering assistance, engaging in friendly conversations, and bridging the gap between humans and AI.
- Seamless user experience: The project aims to provide a seamless and immersive conversational platform, ensuring a smooth and enjoyable user experience.

## Authors

- [@shubham-sapkal](https://github.com/shubham-sapkal)


## Demo

![Demo Video](https://github.com/shubham-sapkal/divineGPT/blob/master/client/demo.mkv)
## Deployment

To deploy this project, enter following commands

```bash
  git clone 
```

```bash
  cd server
```

```bash
  npm install
```

create one file with name .env and paste your openai API key like below:
OPENAI_API_KEY = "<Your API Key>"

```bash
  npm start server
```

```bash
  cd .. && cd client
```

```bash
  npm install && npm run dev
```


## API Reference

#### Get the response of prompt

```http
  openai.Completion.create(
    model="text-davinci-003",
    prompt="Make a list of astronomical observatories:"
  )
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|  `model`  | `string` | **Required**. Name of model |
| `prompt`  | `string` | **Required**. Prompt messsage|






## Contributing

Contributions are always welcome!

Please adhere to this project's `code of conduct`.

