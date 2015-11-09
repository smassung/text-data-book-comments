# Text Data Analysis and Management: A Practical Introduction to Text Mining and Information Retrieval

[ChengXiang Zhai](http://web.engr.illinois.edu/~czhai/) and [Sean
Massung](http://web.engr.illinois.edu/~massung1/), [UIUC Computer Science Department](http://cs.illinois.edu/)

## This GitHub Page

This page has been created for two purposes:

### Hold links to draft chapters

Once a draft chapter is completed, we will link to it in the chapter
titles and descriptions below. All are welcome to watch the book as it
progresses.

### Receive feedback from readers

We'd like to hear your comments, fix errors you spot, listen to your
suggestions, and address issues you find with our book. We will keep track of
your comments via [GitHub
issues](https://github.com/smassung/text-data-book-comments/issues) on this
page.

On the right side of this page, click the Issues link. It will take you to a
screen where you can open a new issue or comment on existing issues. If creating
a new issue, you can select one or more of the following labels for it:

 - Typo: a typing error in the book text such as "infromation retreival"
 - Error: a factual error such as "NDCG only operates on binary relevance
   values"
 - Comment: a general comment about part of the book, such as "I really like the
   chapter on X"
 - Suggestion: such as, "could you expand a little more on the Rocchio feedback
   method?"

We will add more issue labels if necessary. Thanks for your help in creating
this book!

 - [Abstract](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-abstract.pdf) (Draft from 7 November 2015)

## Part I: Overview and Background

This part provides an overview of the motivation and high-level concepts of the
book, and gives readers a roadmap for navigating through the chapters in the
later parts. It also includes a background chapter where basic concepts in
probability and statistics and natural language processing are introduced so
that readers without any knowledge in these areas will have the necessary
background to understand the materials later. This part further includes one
chapter on the [MeTA](http://meta-toolkit.github.io/meta/) toolkit, which will
be the basis for many exercises later. We use this chapter to introduce the
typical architecture of a text mining system, where the search engines will be
shown as a basis for supporting text analysis. Readers with sufficient
background knowledge about these topics can skip part or all of this section.

 - [Introduction](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter01-Intro.pdf) (Draft from 8 November 2015)
   * Text Data *vs* Structured Data
   * Functions of Text Information Systems
   * Conceptual Framework for Text Information Systems
   * How to Use This Book

 - [Background](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter02-Background.pdf) (Draft from 8 November 2015)
   * Probability and Statistics
   * Information Theory
   * Machine Learning
   * Exercises

 - [Text Data
   Understanding](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter03-Text-Data-Understanding.pdf) (Draft from 8 November 2015)
   * History and State of the Art in NLP
   * NLP and Text Information Systems
   * Text Representation
   * Statistical Language Models
   * Exercises

 - [MeTA: A Modern Data Sciences
   Toolkit](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter04-MeTA.pdf) (Draft from 8 November 2015)
   * Design philosophy
   * Setting up MeTA
   * Architecture
   * Tokenization with MeTA
   * Exercises

## Part II: Text Data Access

Text data access is the foundation for text analysis. Text access technology
plays two important roles in text analysis and management applications. First,
it enables retrieval of the most relevant text data to a particular analysis
problem, thus avoiding unnecessary overhead from processing a large amount of
non-relevant data. Second, it enables interpretation of any analysis results or
discovered knowledge in appropriate context and provides data provenance. The
general goal of text data access is to connect users with the right information
at the right time. This connection can be done in two ways: *pull*, where the
users take the initiative to fetch relevant information out from the system, and
*push*, where the system takes the initiative to offer relevant information to
users. The main technology supporting *pull* is search engines which are covered
in detail in one long chapter. The main technology supporting *push* is
recommender systems, covered in a later chapter.

 - [Overview of Text Data
   Access](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter05-Overview-Text-Data-Access.pdf) (Draft from 8 November 2015)
   * Access Mode: Pull *vs* Push
   * Multimode Interactive Access
   * Text Retrieval
   * Text Retrieval *vs* Database Retrieval
   * Document Selection *vs* Document Ranking
   * Exercises

 - [Text
   Retrieval](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter06-Retrieval-Models.pdf) (Draft from 7 November 2015)
   * Vector space retrieval models
   * Probabilistic retrieval models
   * Exercises

 - [Feedback](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter06-Feedback.pdf) (Draft from 19 October 2015)
   * Feedback in the vector space model
   * Feedback in language models
   * Exercises

 - [Search Engine
   Implementation](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter06-Search-Engine-Implementation.pdf)
   (Draft from 15 May 2015)
   * Tokenizer
   * Indexer
   * Scorer
   * Feedback
   * Compression
   * Caching
   * Exercises

 - [Search Engine
   Evaluation](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter07-Search-Engine-Evaluation.pdf)
   (Draft from 30 July 2015)
   * Introduction
   * Evaluation of set retrieval
   * Evaluation of a ranked list
   * Evaluation with multi-level judgements
   * Practical issues in evaluation
   * Exercises

 - [Web
   Search](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter09-Web-Search.pdf) (Draft from 2 November 2015)
   * Web crawling
   * Web indexing
   * Link analysis
   * Learning to rank
   * The future of Web search
   * Exercises

 - [Recommender
   Systems](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter10-Recommender-Systems.pdf) (Draft from 24 October 2015)
   * Content-based recommendation
   * Collaborative filtering
   * Exercises

## Part III: Text Data Analysis

This part covers a variety of techniques for text data analysis, where the goal
is to analyze text data to find interesting semantic patterns and extract
useful knowledge. We cover algorithms for four basic text analysis tasks,
including text clustering, text categorization, text summarization, and topic
analysis, each covered in one chapter. The last chapter of this part takes a
broader view of the problem of text analysis by placing it in the context of
joint analysis of text and structured data, which is generally needed in an
application scenario where we have available both unstructured text data and
companion structured data, and would prefer analyzing all the data for solving
a particular application problem.

 - [Overview of Text Data
   Analysis](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter11-Text-Analysis-Overview.pdf) (Draft from 3 November 2015)
   * Overview of text mining and data analytics
   * Text vs. non-text data: humans as subjective sensors

 - Word Association Mining

 - [Text
   Clustering](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter12-Clustering.pdf) (Draft from 21 October 2015)
   * Overview of clustering techniques
   * Document clustering
   * Term clustering
   * Evaluation
   * Exercises

 - [Text
   Categorization](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter12-Categorization.pdf) (Draft from 9 June 2015)
   * Overview of text categorization
   * Features for text categorization
   * Classification algorithms
   * Evaluation
   * Exercises

 - Opinion Mining and Sentiment Analysis

 - Topic Analysis
   * Overview of topic analysis techniques
   * Basic topic models
   * Advanced topic models
   * Evaluation
   * Applications
   * Exercises

 - [Text
   Summarization](http://sifaka.cs.uiuc.edu/ir/textdatabook/chapters/text-data-book-draft-chapter14-Summarization.pdf) (Draft from 23 June 2015)
   * Overview of text summarization techniques
   * Extractive text summarization
   * Abstractive text summarization
   * Evaluation
   * Applications
   * Exercises

 - Joint Analysis of Text and Structured Data
   * Context and companion structured data of text
   * Contextualized text analysis
   * Integrated analysis of text and structured data
   * Evaluation
   * Applications
   * Exercises

 - A Unified Conceptual Framework for Text Analysis
   * An algebra for text analytics
   * Implementation of analysis operators
   * Workspace management
   * Workflow support and optimization
   * MeTA for Text Analysis and Management
   * Contributing to MeTA
