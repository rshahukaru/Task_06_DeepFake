# Task 06 – DeepFake / AI Street Interview

This repository documents my attempts at creating a “deep fake” or AI-generated street interview based on my prior LLM work. The focus of this task is on the **workflow and documentation** rather than the final polished result.

------------------------------------------------------------------------

## 📂 Repository Structure

```         
Task_06_DeepFake/
├── audio/
│   └── download.wav        # AI-generated TTS audio from Gemini
├── deliverables/
│   ├── image.jpeg           # Realistic AI-generated image (Gemini)
│   ├── workspace.png       # Screenshot of Gemini workspace (speaker detection, TTS settings)
├── scripts/
│   └── interview_v1.txt    # Original interview script
└── README.md               # This file
```

------------------------------------------------------------------------

## 📝 Summary of Workflow

1.  **Initial Attempts at Video Generation**

    -   Tried **invideo.io** → produced stock footage with audio overlays but did not follow my script accurately.
    -   Tried **fal.ai** → required a subscription, so not feasible for this task.

2.  **Pivot to Image & Audio Generation**

    -   Used **Gemini 2.5 Pro Preview** to generate a **realistic interview-style image**.

    -   Used **Gemini TTS tool** to generate **realistic audio**.

        -   Detected multiple speakers automatically.
        -   Inserted natural pauses and breaths.
        -   Produced highly natural, conversational output.

3.  **Documentation**

    -   Collected all results (script, audio, images, screenshots) into this repo.
    -   Reflected on workflow, challenges, and learnings.
