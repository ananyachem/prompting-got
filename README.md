## Prompting GPT

This project uses the OpenAI API to prompt multiple versions of GPT into answering questions from a user-submitted passage. Prompts were tested on GPT-4o-Mini, since it the cheapest model as of now. A comparison accross the GPT-4o, GPT-4o-Mini, and the GPT-3.5-Turbo models was also performed. GPT-40-Mini outperformed the other two models, achieving an Exact Match (EM) score and F1 score of 100%. The BLEU score metric was additionally used for a more lenient evaluation, where GPT-3.5-Turbo performed reasonably well, achieving a BLEU score of around ~70%.

To run this code, generate an API key from OpenAI and create a dot env file in the same folder :) Have fun! (but not too much because it comes with a price)
