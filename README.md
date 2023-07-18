# COP5615 - Distributed Operating Systems Principles - TwitterClone

This project aims to create a Twitter-like engine and web user interface which supports functionalities like register, subscribe, tweet, re-tweet, and search queries based on hashtags and profiles.

## Project Objective

The goal of this project is to construct an engine similar to Twitter, complete with a web interface. This engine will allow users to register, post tweets, and conduct searches. Alongside this, a client simulator will be created to replicate the behavior of thousands of users and evaluate the performance of the distributed engine. The project is divided into two milestones.

### Phase 1

In this phase, we will focus on building the backbone of the Twitter-like engine. We will develop a simulator engine that mimics the activities of various users. It will simulate typical user actions such as registering an account, subscribing to other users, posting tweets, and retweeting posts from other users.

### Phase 2

In this phase, we will incorporate WebSockets to furnish a web interface.

## Project Features

The application will have the following features:

- Register
- Send tweet (tweets can include hashtags, e.g., #topic, and mentions, e.g., @bestuser)
- Subscribe to user tweets
- Re-tweets
- Query tweets by the subscribed user
- Query tweets by Hashtag
- Query tweets by Mentions
- Display the new tweets by subscribed users live (without querying)

## Web GUI

<img width="187" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/1d34c83f-9944-41d7-a65e-9b52064ebf23">


## Technology Used

The project is implemented using the **Erlang** programming language.

## Installation and Execution

### Installation

#### Erlang (on Mac)

```shell
brew install erlang
```

#### Project Code: 

Download files


### Steps to Run the Project:
1. Extract the contents of the zip file.
2. Move to the relevant directory using the command cd and execute “make run”.
- Run the following in terminal
```
cd Twitter
make run
```
3. Navigate to http://localhost:8082 in the browser.
