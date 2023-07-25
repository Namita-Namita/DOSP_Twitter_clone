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

<p><img width="187" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/1d34c83f-9944-41d7-a65e-9b52064ebf23" style="border:1px solid black"> &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img width="194" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/cf1c3e47-95d1-4d76-8bb5-2de02c7d06a8" style="border:1px solid black">&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img width="186" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/89ab6281-c85f-4325-bba5-bce403b496f9" style="border:1px solid black">&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
 <br><em>Fig 1.: User Registration</em>
 &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp; &nbsp;<em>Fig 2.: User Dashboard</em>&nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp; &nbsp;&nbsp;<em>Fig 3.: Hashtag Search not exisitng</em></p>

 
<p><img width="192" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/95556c5c-7dc7-42d9-9e27-a324da59ce59" style="border:1px solid black">
&nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp; <img width="178" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/7d2115cc-6b34-4384-a056-f99863b6266c" style="border:1px solid black"> &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img width="193" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/d71030ab-e3f0-4b59-bb64-bac4775859a8" style="border:1px solid black">
<br><em>Fig 4.: Subscribe</em>&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;
<em>Fig 5.:Successfull Hashtag Search</em>
 &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;<em>Fig 6.: Subdcribed Tweets</em>&nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;</p>

<p><img width="175" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/182f7288-7d32-479e-b9f8-9c024bbdcdfa" style="border:1px solid black">&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img width="188" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/94033d26-4fae-4e6c-9954-31691596330a" style="border:1px solid black">&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;<img width="189" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/cb1e2167-e3dd-42d5-ad29-997fec639d87" style="border:1px solid black"> &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<br><em>Fig 7.:New Tweet</em>&nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp; &nbsp;&nbsp;<em>Fig 8.: Re-tweet</em>&nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp; &nbsp;&nbsp;<em>Fig 9.:Search Mentions</em></p>
<p> <img width="181" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/a8e23567-ab84-4da0-8a96-5752e0e3d1fb" style="border:1px solid black">&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;</br><em>Fig 10.:Search Subscribers</em></p>


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

### 
<img width="468" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/b1f8f3ee-2486-4f33-9c69-24a6c7f20dc3">


### Control Flow
<img width="468" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/cef5e492-7ba4-4679-b26b-290109bc572b">

### Code Snippet
<p><img width="989" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/e44e5111-1bcf-41b1-8219-4982c7de9a56"></p>
server
<p><img width="632" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/c2effb6c-2064-4666-8292-8f5ca655c024"></p>
handler
<p><img width="745" alt="image" src="https://github.com/Namita-Namita/DOSP_Twitter_clone/assets/31967922/b400eff7-482a-4a83-8efd-c8411958cdec"></p>

