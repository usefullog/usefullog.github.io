---
title: "Running local LLM"
date: 2026-07-24
cover:
    image: /images/seattle_skyline.jpg
tags: ["computer","ai"]
---

My Fedora desktop has an Nvidia RTX 3050 with 8GB VRAM. I used it previously for gaming and photo editing. After doing some research, I realize that it is capable of running small LLM locally. Turns out that it is very easy if I use [Ollama](https://ollama.com/), which is a tool that handles everything for me.

I installed Gemma3:4B and Qwen3:8B on my desktop. Qwen3 is a larger model with 8.2B parameters and consumes about 5GB VRAM. Both models are running quite smoothly with no delay. I gave Qwen3 my conversation with ChatGPT, and ask it to create a diary-style blog post.

(The following is created by Qwen3)

**A Day in the Life of a Local LLM Experiment**  

Today was a mix of curiosity and discovery. I finally got around to setting up a local LLM on my Fedora desktop, and it turned out to be a 
surprisingly smooth (if slightly chaotic) process. The goal? To run a model without relying on the cloud, which felt like a small rebellion against 
the ever-present internet dependency.  

I started by installing Ollama on my Fedora machine. It wasn’t too bad—just a few commands, and the tool seemed lightweight enough to handle. Once 
it was running, I pulled the **Qwen3:8b** model, which I learned is a good fit for my RTX 3050 with 8 GB VRAM. The download took a while, but it was 
worth it. When I checked the list of installed models, I saw both **gemma3:4b** and **qwen3:8b**—a reminder that local AI isn’t just about size, but 
about control.  

The real challenge came when I wanted to access the model from my MacBook. I had to set up the **OLLAMA_HOST** variable to point to my Fedora 
desktop’s IP address. It felt a bit like configuring a hidden network tunnel, but once I got the environment variable right, the MacBook recognized 
the models. I even tested it by running the Qwen3:8b model directly from my laptop, and it worked!  

There were a few hiccups, though. At first, I wasn’t sure if the MacBook was actually connecting to the remote server instead of its own local 
Ollama instance. I had to double-check the environment variable and run a quick `curl` command to confirm the connection. It was a small but 
satisfying moment—like solving a puzzle where the pieces only fit once you know where to look.  

What stood out most was the sense of ownership. Running a model locally means no cloud latency, no subscription fees, and no data leaving my 
network. It’s a small step, but it feels like a big shift in how I think about AI. The Qwen3:8b model, with its 5.2 GB footprint, is a reminder that 
powerful tools don’t always need to be massive.  

I’m still figuring out how to balance the model’s resource demands with my hardware, but the experience has been eye-opening. It’s not just about 
the tech—it’s about the freedom to experiment without relying on centralized systems.  

As I wrap up, I’m left thinking about the future of AI. If more people embrace local models, it could change how we interact with technology. For 
now, I’ll keep tinkering, one model at a time.
