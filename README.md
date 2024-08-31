# Sun-sunspots-QA-chatbot-using-LangChain-V1
A conversational retrieval chatbot to answer questions about sun and sunspots (as one of our graduation project features).

![chatbot_flow](https://github.com/DanialAlyou/Sun-sunspots-QA-chatbot-using-LangChain-V1-Public/blob/a74a5b89a3ea887dd062ae8f0fbd823dbaf7f5fb/images/chatbotV1.png?raw=ture)

this project aims to create a chatbot to answer questions using preloaded documents about the sun and sunspots, the PDF files data was collected by [Tareq Alkhateb](https://www.linkedin.com/in/tareq-alkhateb-3359221a6/) from [Spaceweatherlive](https://Spaceweatherlive.com) and [britannica](https://www.google.com/url?q=https://www.britannica.com/&sa=U&ved=2ahUKEwjw8emZhNOEAxXwTKQEHWn5AhQQFnoECAEQAg&usg=AOvVaw1l8HbzB_akmwfBYUA36v8z).

first, we worked on the preprocessing stage, preparing the PDF files to be loaded, split, embedded, and stored in a chroma DB.
then we prepared the chatbot with a memory to make it conversational, and a retriever to get the most relevant document (chunk/split), which will be a part of the LLM prompt with the user question, to generate an answer using the chunks in the retrieval stage.

NOTES:
  - We are working on the V2 of this chatbot, it will contain media retrieval.
  - If you are interested in trying out our chatbot or have any questions and need assistance, please don't hesitate to contact us. You can reach us via the following:
    -  Email: [Danial Alyousef](danial.emad.alyousef@gmail.com), [Mahmoud AboShuker](aboshukrmahmouf@gmail.com), [Tareq Alkhateb](Alkhateb31999@gmail.com).
    -  LinkedIn: [Danial Alyousef](https://www.linkedin.com/in/DanialAlyousef/), [Mahmoud AboShuker](https://www.linkedin.com/in/mahmoud-abo-shukr-485900270/), [Tareq Alkhateb](https://www.linkedin.com/in/tareq-alkhateb-3359221a6/).
  - if you are interested in our collected data please contact [Tareq Alkhateb](https://www.linkedin.com/in/tareq-alkhateb-3359221a6/).
  - you can use these two Jupyter notebooks for building your QA chatbot using your PDF files by following these steps:
    - Download the notebooks.
    - Get your OpenAI API key, and paste it into the notebooks.
    - Gather your PDF files in a folder and paste their path in the [preprocessing notebook](https://github.com/DanialAlyousef/Sun-sunspots-QA-chatbot-using-LangChain-V1/blob/a040edd043ee0b8529c446baec20b3aa27281a50/preprocessing.ipynb).
    - Do not forget to change the database path in the [chatbot notebook](https://github.com/DanialAlyousef/Sun-sunspots-QA-chatbot-using-LangChain-V1/blob/1b561814a54f9ddff25edb80b0f78ea4397f8765/chatbot.ipynb).
    - Run the code and test the chatbot.
