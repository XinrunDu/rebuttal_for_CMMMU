# rebuttal_for_CMMMU

This repository contains three files, each with results from using Yi-VL-6B, Yi-VL-34B, and Qwen-VL-Chat respectively, to infer 200 randomly sampled multiple-choice questions from CMMMU (only including the question stem text, without options and images).

In the JSON files, the prompt is the prompt given to the model, which also includes "A." to guide the model in continuing to write the options. The response is the model's response. It can be seen that the model does not have the intention to continue writing the options, ruling out the suspicion of contamination.