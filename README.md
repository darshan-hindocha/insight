# insight
an general purpose insight generation tool

This will likely rot untouched... but the idea is to create a service that returns patterns from data -- but in sentences, as insights. 

For instance, given some body of text, the tool would look to provide facts and patterns on the data. Something like -> most used words, distribution of words, style of language... 

Similar to what `pandas.DataFrame.head()` gives you for tabular data except we return sentence insights -- and focus on offbeat patterns.

what i think would be hard (other than finding the time);
- scaling up the number of insights. every dataset is different, and so an interesting pattern in one dataset may not be relevant in the other. so we need a large arsenal of insight tools.
- generalising the process of choosing which insights are relevant for which data point
- clarifying the tool


["All open source contributors have a graveyard of old projects."](https://supabase.com/blog/2022/03/25/should-i-open-source-my-company?utm_medium=email&_hsmi=208017676&_hsenc=p2ANqtz-_lgM-J0ZbMa9_ghu0Bb0TimDqHqE7_rpcjU2vP06-_VSZbA74svlItnTWgdoc0yTUEeu3Lyky5RVLwCyZhlV5uW_K3dw&utm_content=208017676&utm_source=hs_email)

That's my excuse for sharing this repo before working on it 😅
