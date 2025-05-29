# Agent-Meme
## Because crafting a clever LinkedIn comment shouldn’t take longer than reading the post.

### Challenge
Crafting sharp, engaging LinkedIn comments is tough without strong synthesis skills. 
With a mix of prompt engineering, Python, and AI collaboration, I built _Agente Meme_ to automate the process: it generates witty replies and turns them into visual memes for high-impact engagement.
This was also a personal challenge in using ChatGPT not just as a tool, but as a creative and technical sparring partner.

### Approach
I developed a Python agent that:
* Accepts any LinkedIn post as input
* Generates 3 short, ironic/witty responses with GPT-4o
* Lets the user select one
* Creates a DALL·E-generated background (with a "no text" constraint)
* Allows customization of ambience (futuristic, pop, etc.)
* Splits the chosen comment into top/bottom lines
* Renders the final meme using Pillow, with dynamic font scaling
* Saves and offers the meme as a downloadable image

### Outcome
A ready-to-use meme for LinkedIn with voice, personality, and style.
This project helped me learn how to:
* Integrate OpenAI’s chat and image APIs
* Handle edge cases in text rendering
* Tweak prompts to reduce DALL·E’s unwanted text artifacts
* Automate creative content generation from input to final asset

### Reflections
It wasn’t just about code, it was about controlling creativity.
This project confirmed to me that knowing how to guide an AI by asking the right questions is a powerful technical skill. ChatGPT helped a lot, but the real work was in framing, testing, and iterating with intention.
Despite prompt constraints, DALL·E often insists on drawing text, revealing the current limits of LLM-based image generation.
Still, the output is punchy, unique, and fully automated.




