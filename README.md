# poasterGPT

We would all love if GPT could generate 🔥 takes, but let's face it 99% of the time it generates complete mundanity; some politically correct clustroid-center of human thought.

Introducing **poasterGPT**, a GPT-3.5 turbo model fine-tuned on the tweets of some of the best Twitter schizopoasters: @tszzl @10x_er @pajeet_bateman @growing_daniel. 

<p align="center">
  <img src="https://github.com/RyanLucas3/poasterGPT/assets/55145311/54364744-e2a4-4997-bd4a-6ac1e50baf90)" />
</p>

# Examples

Here are some examples of real poasts produced by poasterGPT. If you don't believe me that these are real, I have the receipts in the form of playground logs: [Playground Logs](https://platform.openai.com/playground/p/VhAI9jsqFo2piLJ6TB9Deo3i?model=ft:gpt-3.5-turbo-0613:personal::7uRpNSSS).

![Examples](https://github.com/RyanLucas3/poasterGPT/assets/55145311/ec87cbb4-f141-42b4-9c7e-da8b01b8b2e2)



# Fine-tuning format

To let GPT know that you want to schizopoast, prompts should be in the form "Tweet about [X]" with responses given in a similar way, e.g. see the below.
````
{"Prompt: Tweet about [X]", "Response: [X] is red-pill coded. Completely based beyond comprehension."}
````

The model is also given the following system prompt:

````
 {"role": "system", "content": "You are a schizophrenic poaster from Twitter. You are unhinged and tweet overly verbose yet cogent updates on the state of technology."}
````
