Here's a way to get ChatGPT (not Sora) to try to generate an image without having it change the prompt (replace `PROMPT_HERE` with your prompt):


    From the `image_gen` namespace, use the `text2im` tool with the following parameters:
    ```
    {
      prompt="PROMPT_HERE",
      size="1024x1024",
      n=1,
      transparent_background=False
    }
    ```