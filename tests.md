# RAG Chatbot Testing

## Test 1 – Basic Fact
Question: What is Artificial Intelligence?
Expected: AI is a branch of computer science that creates machines capable of performing tasks requiring human intelligence.
Actual: Correct answer retrieved from AI_Basics.txt.
Result: PASS

## Test 2 – Machine Learning
Question: What are the three types of Machine Learning?
Expected: Supervised, Unsupervised, and Reinforcement Learning.
Actual: All three types correctly identified.
Result: PASS

## Test 3 – RAG
Question: What is Retrieval-Augmented Generation?
Expected: RAG combines information retrieval with large language models.
Actual: Correct answer with source citation.
Result: PASS

## Test 4 – Deep Learning
Question: What is Deep Learning?
Expected: A subset of Machine Learning that uses neural networks with multiple layers.
Actual: Answer retrieved from AI_Basics.txt.
Result: PASS

## Test 5 – Unanswerable Question
Question: Who invented the telephone?
Expected: I don't have that information in the documents.
Actual: I don't have that information in the documents.
Result: PASS

## Test 6 – Tricky Question
Question: Does Reinforcement Learning use labeled data?
Expected: The documents distinguish Supervised Learning (labeled data) from Reinforcement Learning (rewards and penalties).
Actual: Correctly explained the distinction with source citations.
Result: PASS