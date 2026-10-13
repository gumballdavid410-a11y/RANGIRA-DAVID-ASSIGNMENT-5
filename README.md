[README.md](https://github.com/user-attachments/files/33383537/README.md)
# Assignment 5 — Campus Library Chatbot

**Student:** Rangira Rurangwa David  
**Course:** Chatbots Development (AITCD001)

## Overview
This Week 5 assignment upgrades the Assignment 4 rule-based campus library chatbot. It demonstrates a router connected to handler functions, a greeting handler, overdue-fine calculation, multiple requests in one message, and memory across turns.

## Files
- `RANGIRA_RURANGWA_DAVID_Assignment_5.ipynb` — runnable Jupyter Notebook containing the implementation, demonstrations, eight test conversations, and written reflection.

## Requirements
- Python 3
- Jupyter Notebook or Google Colab

The notebook uses only Python's standard library (`re`), so no additional packages are required.

## How to Run
1. Open the notebook in Jupyter Notebook or upload it to Google Colab.
2. Run all cells from top to bottom.
3. Review the printed demonstrations and the eight test-conversation results.
4. Confirm that the two documented limitations are recorded and explained.

## Features
- Handler router for greetings, opening hours, borrowing, renewals, fines, study rooms, and printing.
- Fine calculation at 200 RWF per overdue day, capped at 5,000 RWF.
- Detection of several supported requests in one message.
- Memory for the user's name and a numeric fine follow-up.
- Multi-turn study-room booking with day, time, number of people, confirmation, and a side-question path.
- Eight test conversations, including two documented failures/limitations.

## Notes
The study-room booking is a simulation. It does not check real room availability or save reservations to a library system. The chatbot uses simple pattern matching and has the limitations discussed in the notebook.
