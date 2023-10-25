# SD-AI-Prompt
A shortcut instruction based on LLama 2 to expand the stable diffusion prompt, Power by llama.cpp.


  Some prompt magic for LLama is used. The generated SD prompts are perfect and appropriate natural language descriptions.
  
  SDXL can understand and restore these descriptions well, which is much better than using a lot of phrases.
  
  There is no use of the prompt prefix specified by LLama 2, but it is better now, and there will be no unwanted expressions.
  
  Because it needs to end automatically after running, it is impossible to intercept the ending suffix symbol. 
  
  Sometimes two prompts may be generated, using double time, but the shortcut will be filled with the correct prompt.
  

- Install shortcuts from the following address:
  
  [https://www.icloud.com/shortcuts/1b32e87152e84bbeb4aa74ed88c9bc38](https://www.icloud.com/shortcuts/93ae5c2c26a246878ae6d666f87c8ba3)
  
  2023/10/25 update：Solve the problem that the prompt may not meet expectations.

- Then edit it and modify the directory where llama.cpp main is located and the model directory as shown in the figure below.

  The parameter configuration turns on GPU acceleration by default. It is recommended to use the Llama-2-7b-chat-q4_1.gguf model.

  (If you haven't used llama.cpp, please learn about this project first, With the following parameters, the startup speed will be faster, and the --prompt-cache-ro parameter should be removed for the first time.)
  
  `--prompt-cache ./cache.gguf --prompt-cache-ro`

<img width="887" alt="modify" src="https://github.com/czkoko/SD-AI-Prompt/assets/90698189/620e4252-6503-4148-8653-a11f5491b410">




https://github.com/czkoko/SD-AI-Prompt/assets/90698189/abe35a73-70ca-49cf-8cb2-bbffcb77eabe


Original Prompt: `Magic Forest`

AI Prompt: `A dense and enchanted forest with towering trees, twisted branches, and glowing mushrooms, a group of creatures and fairies flitting about in the distance, soft and warm lighting, close-up shot, dreamy tone.`
![IMG_00051](https://github.com/czkoko/SD-AI-Prompt/assets/90698189/4fad3900-da8b-4e3b-ad1b-2b6182b7cf15)



Original Prompt: `a beautiful woman`

AI Prompt: `A stunningly beautiful woman with long blonde hair and piercing blue eyes, standing on a rocky cliffside overlooking the ocean, the sun setting behind her, Wide-angle shot, dramatic lighting, warm color tone.`
![IMG_00052](https://github.com/czkoko/SD-AI-Prompt/assets/90698189/9f84d4c4-a9fe-4686-ba55-492640080154)


You can also specify the picture style, just like this:

Original Prompt: use cartoon style, A girl sitting in a coffee shop

AI Prompt: a cute young girl with pink hair and big blue eyes sitting at a small table in a cozy coffee shop, surrounded by warm colors and soft lighting, cartoon-style illustration.
