# Large-Language-Model 
# Prime Minister Information Generator

![Project Logo](llm7b.png)

## Introduction

Welcome to the Prime Minister Information Generator project! In this project, we explore the world of data processing and language models to extract insightful information about Pakistan's Prime Ministers. By fine-tuning a large language model, we're able to generate detailed answers to specific questions about their tenures, achievements, and more.

## Project Overview

- **Dataset:** We start by loading historical data about Pakistan's Prime Ministers into a DataFrame.
- **Data Formatting:** The data is structured into a dictionary format, making it compatible with the language model.
- **Fine-Tuning:** Utilizing the TRL (Text Representation Learner) library, we fine-tune a large language model to understand and generate human-like text.
- **Training Phase:** The model undergoes a training phase, learning to respond accurately to our prompts.
- **Generating Answers:** Using the trained model, we generate answers to questions about Prime Ministers.
- **Formatting Output:** The generated responses are formatted for clarity and readability.

## How to Use

1. Install the required libraries using `pip install transformers trl pandas`.
2. Load your data into a DataFrame.
3. Format the data into a dictionary structure compatible with the language model.
4. Fine-tune the language model using the TRL library, specifying training parameters.
5. Generate answers by providing prompts to the trained model.
6. Format and present the generated output for readability.

## Acknowledgments

A special thank you to Sir Qasim for his invaluable guidance and support throughout this project. His expertise has been instrumental in bringing this project to fruition.

## About the Model

We used the Large Language Model Lamma-2, boasting an impressive 7 billion parameters, to achieve accurate and coherent responses to our prompts.

## Example

**Question:** Who is the Prime Minister in 2021 in Pakistan?

**Answer:** As of 2021, the Prime Minister of Pakistan is Imran Khan. Elected in the general elections held on July 25, 2018, he took office on August 18, 2018. Imran Khan is the leader of the Pakistan Tehreek-e-Insaf (PTI) party and has led the country since then.

## Conclusion

This project showcases the synergy between data processing and language models, providing insights into Pakistan's political history. Feel free to use this project as a reference to extract information or generate answers in various contexts.


---

