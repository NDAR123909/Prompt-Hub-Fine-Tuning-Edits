# 06-24-2024 Changelog

This update mostly aims to fine-tune the existing writing prompts in the Salina Prompt Hub to help them avoid generic AI-clichés while also making sure that their generated text isn't wordy.

## New Additions

- All existing writing prompts will contain blacklisted words that should not be included in the generated outputs
  - These words to avoid will be included in the prompt as well as in the reference files of the Salina Instructbots themselves
  - "Words to Avoid" reference file: https://drive.google.com/file/d/1yGBfDt5DIKr5A5eYwNiKmvGQOEG9dIMU/view?usp=sharing
    
- All existing writing prompts will also include "no yapping and/or words to avoid" as part of the prompt
  - This segment in the prompt will reduce the length of the agents' outputs
  - It also aims to make the outputs less GPT sounding
  - "No yapping metaprompt + words to avoid" was only added to prompts that generated AI-written content.
      - Only the "No yapping" metaprompt was added to prompts that did not aim to generate content on its own (content review/strategy/outlining prompts)
        
- All instructbots affected by all of these changes were provided the "words to avoid" reference file 
