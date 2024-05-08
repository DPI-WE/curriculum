# Web apps with Sinatra & OpenAI API
- Overview: Web apps with Sinatra & OpenAI API
```md
This module is about making API requests to OpenAI with a Sinatra app.  You will be introduced to securing requests with POST methods and API keys.

## Objectives
After successful completion of this module, you should be able to:

- Build a web app with the Sinatra framework
- Make external API requests
- Interpret API responses

## Activities
- Mark each page as Done
- Complete and achieve the 1 point score in the lesson: Example OpenAI API request 
```

- Explore the OpenAI GPT-4 API 🚀🧠🌐
```md
If you've used ChatGPT before, then you have been interacting with OpenAI's API. ChatGPT is a product OpenAI built to show off the capabilities of their API, but they really make their money by selling API access to developers.

If you haven't used ChatGPT before, or even if you have, [the video OpenAI published introducing GPT-4](https://www.youtube.com/watch?v=hdhZwyf24mE) gives a good sense of its unique capabilities, and might give you ideas of prompts to experiment with.

If you want to explore this new revolution we're living through, I recommend that you [sign up for an OpenAI developer account](https://platform.openai.com/signup). You'll get $120 worth of free credit (at the time of this writing), but it requires a credit card to sign up. Once you sign up, you can then experiment in [the API playground](https://platform.openai.com/playground?mode=chat).

If you experiment in the playground a little, you may notice that the results from the `gpt-3-turbo` model are not nearly as good as the results that you see on ask.firstdraft.com (which uses `gpt-4`). `gpt-4` is not yet available to everyone. I suggest you add yourself to the waiting list for `gpt-4`.

Don’t share your API key with anyone. Really.
You can use this [unofficial client](https://chatwithgpt.netlify.app/) to experiment with the api key. Click the “customize system prompt” link at the bottom to simulate the official API playground.
Yes, we’re taking risk by pasting an API token into this 3rd-party client. It's okay for now.
When you get to using the token in your own code, be sure to [store it securely in an environment variable](https://learn.firstdraft.com/lessons/52).
```

- Example OpenAI API request 🚀🧠🌐
  - [Learn](https://learn.firstdraft.com/lessons/121)
  - [GitHub](https://github.com/appdev-lessons/openai-api-example)

- The POST verb 📌 📋
  - [Learn](https://learn.firstdraft.com/lessons/115)
  - [GitHub](https://github.com/appdev-lessons/the-post-verb)

- Sinatra: Omnicalc 3 🌐🧮
  - [Learn](https://learn.firstdraft.com/lessons/118)
  - [GitHub](https://github.com/appdev-lessons/sinatra-omnicalc-3)

- (Optional) Artificial Intelligence Readings
```md
Here is a list of AI resources. I hope it gives you an idea of the overall timeline, and an appreciation of how incredibly rapid recent developments have been coming. **This assignment is entirely optional; only proceed if you're interested and have time to kill**.

1950s-2010s: [A “Brief” History of Neural Nets and Deep Learning](https://www.skynettoday.com/overviews/neural-net-history)

2016: [AlphaGo - The Movie | Full award-winning documentary](https://www.youtube.com/watch?v=WXuK6gekU1Y)

2016: [The Great A.I. Awakening](https://archive.is/aKRem)

2020: [OpenAI’s GPT-3 may be the biggest thing since bitcoin](https://maraoz.com/2020/07/18/openai-gpt3/)

2020: [CASP14: what Google DeepMind’s AlphaFold 2 really achieved, and what it means for protein folding, biology and bioinformatics](https://www.blopig.com/blog/2020/12/casp14-what-google-deepminds-alphafold-2-really-achieved-and-what-it-means-for-protein-folding-biology-and-bioinformatics/)

Oct-2022: [DeepMind breaks 50-year math record using AI; new record falls a week later](https://arstechnica.com/information-technology/2022/10/deepmind-breaks-50-year-math-record-using-ai-new-record-falls-a-week-later/)

Dec-2022: [Building A Virtual Machine inside ChatGPT](https://www.engraved.blog/building-a-virtual-machine-inside/)

Mar-14-2023: GPT-4

Mar-21-2023: [Bill Gates: The Age of AI has begun](https://www.gatesnotes.com/The-Age-of-AI-Has-Begun)

Mar-23-2023: [ChatGPT Gets Its “Wolfram Superpowers”!](https://writings.stephenwolfram.com/2023/03/chatgpt-gets-its-wolfram-superpowers/)
```
