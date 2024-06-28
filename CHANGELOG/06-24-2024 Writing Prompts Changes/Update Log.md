## 06-24-2024 Update Log

- All existing writing prompts will contain blacklisted words not to include in the generated outputs
  - These words to avoid will be included in the prompt as well as in the reference files of the Salina Instructbots themselves
  - "Words to Avoid" reference file: https://drive.google.com/file/d/1yGBfDt5DIKr5A5eYwNiKmvGQOEG9dIMU/view?usp=sharing
- All existing writing prompts will also include "no yapping and/or words to avoid" as part of the prompt
  - This segment in the prompt will reduce the length of the agents' outputs
  - It also aims to make the outputs less GPT sounding
  - "No yapping metaprompt + words to avoid" was only added to prompts that generated AI-written content.
      - Only the "No yapping" metaprompt was added to prompts that did not aim to generate content on its own (content review/strategy/outlining prompts)
- All instructbots affected by this change were provided the reference file (but not necessarily the "words to avoid")
