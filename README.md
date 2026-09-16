# Applied Unsupervised & Reinforcement Learning

Practical implementation of **Unsupervised Learning** and **Reinforcement Learning** concepts using Python and scikit-learn, with a focus on understanding their applications in business decision-making.

## Overview

This repository contains a practical notebook demonstrating two machine learning approaches:

* **Unsupervised Learning** — customer segmentation using K-Means Clustering
* **Reinforcement Learning** — route selection using actions, rewards, exploration, and exploitation

The practical is designed to connect machine learning concepts with simple and understandable business use cases.

## Objectives

By completing this practical, you will learn how to:

* Segment customers using K-Means clustering
* Identify groups with similar customer behaviour
* Interpret machine learning clusters from a business perspective
* Understand the basic Reinforcement Learning framework
* Identify an Agent, Action, Environment, and Reward
* Understand Exploration vs Exploitation
* Connect ML outputs with business decision-making

## Project Structure

```text
applied-unsupervised-reinforcement-learning/
│
├── part-a/
│   └── unsupervised-learning/
│       └── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│
├── README.md
└── screenshots/
    └── customer-segmentation.png
```

## Part A — Customer Segmentation

The notebook uses **K-Means Clustering** to divide customers into three groups based on:

* Monthly Spending
* App Visits

The customer identifier is not used as a clustering feature.

### Business Use Case

Customer segmentation can help businesses understand different customer behaviour patterns and design appropriate actions such as:

* Loyalty rewards
* Personalized recommendations
* Re-engagement campaigns

The cluster numbers themselves do not represent customer quality; they are simply labels assigned by the clustering algorithm.

## Part B — Reinforcement Learning

The practical introduces Reinforcement Learning through a delivery-route scenario.

The system chooses between:

* Route A
* Route B

The routes receive different rewards based on delivery performance.

### RL Components

| Component   | Example                       |
| ----------- | ----------------------------- |
| Agent       | Delivery decision system      |
| Environment | Roads and traffic             |
| Action      | Choose Route A or Route B     |
| Reward      | Delivery performance feedback |

## Exploration vs Exploitation

### Exploration

Trying a new or less-used option to gather more information.

**Example:** Trying Route A even when Route B has previously performed better.

### Exploitation

Using an option that is already known to perform well.

**Example:** Choosing Route B because it has previously provided higher rewards.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

## Machine Learning Concepts

| ML Type                | Main Idea                      | Example                   |
| ---------------------- | ------------------------------ | ------------------------- |
| Supervised Learning    | Learn from known answers       | Customer churn prediction |
| Unsupervised Learning  | Discover hidden patterns       | Customer segmentation     |
| Reinforcement Learning | Learn from actions and rewards | Route optimization        |

## How to Run

1. Clone or download this repository.
2. Open the `.ipynb` notebook in **Google Colab** or **Jupyter Notebook**.
3. Install the required Python libraries if necessary.
4. Run the notebook cells sequentially.
5. Review the clustering visualization and business interpretation.
6. Review the Reinforcement Learning reward calculations and examples.

## Key Learning Outcomes

This practical demonstrates how machine learning can move beyond prediction and support business decisions through:

* Pattern discovery
* Customer segmentation
* Behaviour analysis
* Reward-based decision-making
* Route optimization concepts

## Repository Status

**Educational / Practical Project**

This repository is intended for learning, experimentation, and demonstrating fundamental machine learning concepts through business-oriented examples.
