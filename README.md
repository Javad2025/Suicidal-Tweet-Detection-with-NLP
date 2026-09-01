🧠 Suicidal Tweet Detection with NLP

📌 Project Overview

This project explores how Natural Language Processing (NLP) and Transformer-based language models can be used to classify social media text into two categories:

Not Suicide Post 63%

Potential Suicide Post 37%

total data: 1778 rows

The goal of the project is to build an NLP classification pipeline that can identify linguistic patterns associated with potentially concerning content in tweets.

This project builds on concepts learned from previous NLP work, including text preprocessing, tokenization, token IDs, embeddings, contextual representations, Transformer architectures, and text classification.
📊 Dataset

Dataset: Suicidal Tweet Detection

The dataset contains tweets together with an annotation indicating whether the text is considered a potentially suicidal post or a non-suicidal post.

The dataset was internally generated for an NLP project.

Dataset Structure

Column

Description

Tweet

Text content of the tweet

Suicide

Classification label

The target variable contains two classes:

Label

Meaning

Not Suicide post

The tweet does not contain indicators classified as suicidal content

Potential Suicide post

The tweet contains indicators classified as potentially suicidal content
