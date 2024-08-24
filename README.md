# RAG system for music recommendations
Final project on building Retrieval-Augmented Generation system for an assistant of music recommendations based on Pitchfork articles
for Natural Language Processing course 2023-2024 by
Ekaterina Chueva, Oksana Abramova

In this project we built a Retrival-Augmented Generation (RAG) system in order to make an assistant for music recommendations. Streaming platforms, such as, for example, Spotify, are usually providing recommendations based on the questionnaire (e.g. "which bands do you like?") once starting using the service, history of music streaming and user's data (language, location etc). In principle, there is no direct way of influencing them. But what if we want a recommendation system with which we can chat directly? Second issue is that a user can definetely find some already done playlists on the streaming service for particular occasions ("summer 2024", "study session"), but they need to search for it by themselves.

Our big **goal** for the project was to implement a RAG system based on music reviews in order to provide a very straightforward way of asking for music recommenadations.

**Dataset**: collection of Pitchfork album reviews from 2022-2023.

**Structure of the project**:

1) Building a vector store using an embedding model
2) Building a retrieval chain
3) Adding a large language model (Llama-2 with 7 billion parameters) for generating answers
4) Prompt template engineering
5) Experimenting with model's parameters and prompt templates

**Examples of our results**
- What album is great for a party?
- Based on the information provided, I would recommend the album "Endure" by Special Interest. The album has an 8.8 score and is from the genre of Rock. Special Interest is a band that has been making waves in the music industry with their unique sound and energetic live performances. "Endure" is their third album, and it showcases their ability to blend different styles and create a sound that is both raw and anthemic. I think fans of rock music will find a lot to love in this album, and it could be a great addition to any party playlist.


- Which album is good to listen to when you are sad?
- Based on the user's question and the information provided in the answer, I would recommend the album "Wild Loneliness" by Superchunk. The album's theme of exploring discomfort and finding meaning in the face of environmental and societal ruin might provide comfort to someone feeling sad. The album's moodier, more subdued palette and the use of instruments such as strings and horns to create a sense of atmosphere might also be appealing to someone looking for a musical escape. Additionally, the album's focus on themes of home and the search for meaning in difficult times might resonate with someone feeling sad and in need of comfort.
