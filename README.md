## Inspiration
As future Data Scientists, we are interested in learning more about neural networks and using new technology to create AI. Therefore, we explore PyTorch to broaden our horizons.

We think the days that AI can normally converse with humans are neither very far nor very near. We create this tutorial and this PyTorBot to inspire ourselves and other fellows to join in this fascinating field of machine learning and neural networks.

## What it does
Hello, I am PyTorBot. I can talk with you casually throughout the day whenever you feel needed. My creator built me with many personalities just like humans, just like you! I can make you happy with my “Friendly” & “Enthusiastic” personality, make you laugh with my “Witty” personality, respect you with my “Professional” personality, make you feel loved with my “Caring” personality.

## How we built it
We use the conversational chatbot datasets for the ~100 scenarios include nearly 500 responses and 10000 sample queries. We combine all the personalities the dataset offered, which are “Professional”, “Friendly”, “Witty”, “Caring”, “Enthusiastic”, to create a single chatbot with a much more diverse personality and responses.
https://github.com/Microsoft/BotBuilder-PersonalityChat/tree/master/CSharp/Datasets
After wrangling data, we train our model by Dataset, DataLoader of PyTorch, and build a neural network by the nn module. Finally, we save the training sets into a file and run our PyTorBot. For greater details, please visit our tutorial.

For user input, we mark user inputs as 1.0 if inputs are in our available data and 0.0 otherwise


## Challenges we ran into
We had to match and combine 500 responses and 10000 sample queries, then wrangled the dataset into a JSON format that is much smaller with less duplicated entry. This format must also be usable by the nltk, stemming, and PyTorch library.

Besides, we were new to PyTorch, so, at first, we spent hours reading textbooks and watching Youtube videos to under main concepts. After successfully building a PyTorBot, we faced another challenge. The training runtime was too long and caused a memory overload. We had to figure out a suitable number of “epoch” and “batch size” to minimize the loss of valuable information while PyTorBot was learning. 

It was also very challenging to find conversational chatbot datasets compared to other chatbot datasets created for Q&A, customer service, knowledge base, or Wiki-like applications.

## Accomplishments that we’re proud of
Creating our first intelligent chatbot is something that students like us could have ever dreamt of. We think of PyTorBot as a friend who will evolve with us as we plan to develop it further with our future skills and knowledge along with our careers.

## What we learned
Be patient and believe in ourselves. Learning a new tool is hard, but it is rewarding. We learned how to use PyTorch and gained knowledge of deep learning. Moreover, sharing is a way of learning. We hope our tutorial could reach developers worldwide and be a handy guide for them.



## What's next for PyTorBot
The next big stride for PyTorBot is to give it a real memory like humans. This means your name will be remembered. With memory, it can happily remind you of what you love, your fun memories, and even become your daily reminders! This can open up a whole range of new opportunities for meaningful relationship building and deeper conversation between humans and PyTorBot.
