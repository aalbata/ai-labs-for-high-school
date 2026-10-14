# Hands-On AI for High School

Free artificial intelligence labs for high-school students (grades 9 to 12), by Dr. Ali Al Bataineh, Higher Colleges of Technology, United Arab Emirates.

![Code: MIT](https://img.shields.io/badge/Code-MIT-blue.svg)
![Content: CC BY 4.0](https://img.shields.io/badge/Content-CC%20BY%204.0-lightgrey.svg)
![Audience: Grades 9-12](https://img.shields.io/badge/Audience-Grades%209--12-6B1E2B.svg)

The labs run real AI models in a web browser. You do not need to install anything or know how to code, and nothing costs money. In each lab you see what an AI system does, where it goes wrong, and why.

## Why I made this

I believe knowledge should be shared, and that no one should have to pay to learn.

AI is already part of the apps you use every day, but most high schools do not yet teach how it works. Some students get that chance through a good teacher or a paid program; many do not. I made these labs so that any student with a web browser can learn it for free.

The labs also show AI as it really behaves. You will see a model make confident mistakes, and you will see how its training data shapes what it gets right. Understanding that will help you use AI with care and, one day, build better systems yourself.

Everything here is free and will stay free. If it helps you, please share it with a friend or help someone who is just starting.

Ali Al Bataineh

## The labs

The labs work best in this order. The opening demo takes about 15 minutes and each of the others about 45 to 60.

| Lab | What you will learn | Open it | Printable guide |
|---|---|---|---|
| Opening demo | How an AI can sound right and still be wrong, how a face-analysis system was far less accurate for some people than for others, and how AI can help design lighter, stronger parts. | [Open the demo](https://aalbata.github.io/ai-labs-for-high-school/demos/ai_demo.html) | [Slides (PowerPoint)](slides/ai_demo_slides.pptx) |
| Object recognition with YOLOv8 | How an object-detection model finds things in a photo, what a confidence score does and does not tell you, and why darkness and unfamiliar scenes cause mistakes. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aalbata/ai-labs-for-high-school/blob/main/notebooks/object_recognition_yolov8.ipynb) | [Student guide](guides/object_recognition_student_guide.pdf) |
| Sensor data and anomaly detection | How a short algorithm can spot a failing machine in its sensor readings, how to balance false alarms against missed failures, and why several sensors work better than one. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aalbata/ai-labs-for-high-school/blob/main/notebooks/sensor_anomaly_detection.ipynb) | [Student guide](guides/sensor_anomaly_student_guide.pdf) |
| Grid World (reinforcement learning) | How a robot learns from rewards and penalties instead of from labeled examples, and how the settings and the rewards you choose change what it learns. | [Open the demo](https://aalbata.github.io/ai-labs-for-high-school/demos/grid_world.html) | [Worksheet](guides/grid_world_student_worksheet.pdf) |

## How to start

1. For the two Colab labs, click the Open in Colab badge. Google Colab is free; you only need a Google account.
2. To keep your answers, choose File, then Save a copy in Drive, before you start.
3. Run the cells in order from the top. Click the play button on the left of a cell and wait for it to finish before you run the next one.
4. Read the notes between the cells and write your answers in the Checkpoint and reflection cells.
5. If you prefer to work from paper, the printable guide follows the same steps.

The opening demo and Grid World need only a browser. You can also download the files in the `demos` folder and open them directly.

## License

- Code and notebooks: [MIT License](LICENSE).
- Guides, slides and other text: [Creative Commons Attribution 4.0 (CC BY 4.0)](CONTENT-LICENSE.md).

You may use, adapt and share all of it, including in a class, a club or a summer program. Please credit it as "Hands-On AI for High School" by Dr. Ali Al Bataineh, Higher Colleges of Technology.

## Questions and corrections

If something does not work or you find a mistake, please open an issue on GitHub or write to aalbataineh@hct.ac.ae.
