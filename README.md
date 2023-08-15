# screen_automation_chatgpt

This is no longer relevant with the public release of GPT-4 API


A project to automate the use of GPT-4 to create personalized brand text by modifying existing text without access to the API.

As of the time of writing, it is extremely challenging to get access to GPT-4 via OpenAI's API. As a result, a lot of the advantages it provides in the way of time saving via automation are severely curtailed. 
This project is a result of that circumstance. Its primary purpose is to provide a personalized brand text for cold emails by combining prompt elements with certain raw brand text scraped from the website of prospects. 
While the code is publically available, due to agreements with clients for whom I wrote it, the specifics about what raw brand text was scraped, and the prompt elements it is added to must remain private. I would encourage you to experiment with different prompting to find what works best for your needs. If you need assistance, OpenAI has partnered with DeepLearning.AI to provide this free prompting course (~1 hour) https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/ . The prompts used here rely heavily on few-shot prompting techniques https://www.promptingguide.ai/techniques/fewshot .
This is part of a larger set of prompts using chain-of-thought prompting https://www.promptingguide.ai/techniques/cot

This code has been written specifically to solve the problem discussed above, but could easily be modified to run any sort of prompt using screen automation. Comments within the code point out opportunities to modify certain elements.

Finally, this code was written to be run on machine using Windows operating systems. Several elements using pyautogui will not work with macOS without change.
