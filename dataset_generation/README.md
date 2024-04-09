# The Illustrated Primer Dataset Generator
This is the code to use Python to generate an LLM question & answer finetune training dataset from a PDF textbook. Parses the textbooks, divides into chapters, uses Claude Opus to generate question & answer pairs for each chapter, stores as a JSON.