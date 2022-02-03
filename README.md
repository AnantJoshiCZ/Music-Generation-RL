# <p align="center"> RL Music Generation </p>

<p align="center"> Tunes using Deep RL  </p>

---

This project is was created to explore the role of AI in the creative arts (music). Using Deep RL (DQN) and the rules of music theory, I tried to emulate what might be "creative" or "original" music. 


Music Generation specifically is a task that machine learning should be good at as it contains sequences of notes and fairly structured overall. Models should and do learn it fairly well, but a lot of RNN-based models attempt to extract this structure and use it to learn what sequences should be played. It does not actually choose any new notes on anything other than what has been previously found. Here's where RL comes in. Reinforcement Learning by definition is choosing actions to maximize rewards and learning which notes best follow others. But the most important aspects, in my opinion, is how RL can be used to add _exploration_ to the mix. RL models/agents can choose to ignore the best possible option and instead choose a random action (or note). This feature is amazing because it intuitively allows the agent to keep trying new notes to see which is the most rewarding. Regardless, these notes still exist within the composition and forever change it. This is the creative aspect (which is almost human) which tries new things to find a better way. Anyway, enough talk, here's a sample of what this model has generated: 



