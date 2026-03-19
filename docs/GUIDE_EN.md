# LLM_HumanMode – How to use

## What is it

LLM_HumanMode is a JSON file with a system prompt. It makes the AI respond like a real person: no lists, formatting, emojis, or AI clichés.

## Quick start

### Step 1: Open your AI chat
Go to ChatGPT, Gemini, Qwen, or any other AI chat interface.

### Step 2: Upload the prompt file
- Click 📎 (paperclip) or the file upload button
- Select: `prompts/ru-v1.json` (for Russian) or `prompts/en-v1.json` (for English)
- Send the file to the chat

### Step 3: Wait for processing
The AI will read the file and apply the style settings. Usually takes a few seconds.

### Step 4: Write your request
Just ask your question or describe your task as usual. For example: Explain the difference between Python and JavaScript.

### Step 5: Check the result
The AI will respond in human style:
- Continuous text, no lists
- No bold, italic, or code blocks
- No emojis or decorative symbols
- Like a message from a real person

## Example conversation

**You:** [upload file `ru-v1.json`]

**AI:** [confirms upload]

**You:** Tell me how to choose a laptop for programming

**AI:** Look, it depends on what exactly you're planning to do. If web development – something mid-range is fine, i5 processor or equivalent, 8-16 GB RAM. If machine learning or heavy tasks – better get something more powerful right away, 32 GB and a good GPU. And a comfortable screen, otherwise your eyes will get tired.

## If it doesn't work

**Problem:** AI ignores the file  
**Solution:** Some AI chatbots don't support JSON upload. Try:
- Open the file in a text editor
- Copy the content
- Paste into chat with message: «Apply this system prompt»

**Problem:** AI still writes in lists  
**Solution:** Write in your next message: «Remember: write like a human, no lists or formatting»

## Which file to choose

| File | When to use |
|------|-------------|
| `ru-v1.json` | If you write in Russian |
| `en-v1.json` | If you write in English |
