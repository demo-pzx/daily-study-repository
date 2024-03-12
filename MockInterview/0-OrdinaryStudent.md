# 0 - A MockInterview With An Ordinary Student

> **Keywords**: `Java User`, `Distributed System Design`, `Data Storage`, `Data Structure`, `Backend`, `Operating System`<br/>
> **First Impression We Need**: `Communication`, `Problem-Solving`, `Coding`, `System Design`, `Feedback`<br/>

## Business understanding

> Thirty minutes To make sure you actually have experience using it.

### Question 1: I have noticed that you have developed an application what named as "模型资讯系统," can you tell me more about it?

#### SubQuestion 1: "主要功能是推送最新上传的资讯，支持用户修改个人信息、上传与修改词条," Can you tell me more about what kind of information you are pushing to the user? What's mean in the "词条?"
#### SubQuestion 2: You mentioned that you are using `Mico-Service` to build the system, can you tell me why you choose the `Mico Service`? What's the benefit of it?
#### SubQuestion 3: You mentioned that you are using `Spring Secuirty` to secure the system, can you tell me more about how you secure the system? What's the benefit of it? Or more detail about the `Spring Security`?
#### SubQuestion 4: What's the `JWT`, and how you use it in your system? Out of the `JWT`, do you have any other way to secure the system?
#### SubQuestion 5: Do you have a `sign-on` system in your application? If yes, can you tell me more about how you implement it? If no, why you don't have it? If you have a chance to implement it, how you will do it?
#### SubQuestion 6: Do you know about the `SQL Injection`? How do you prevent it in your system?
#### SubQuestion 7: I have noticed that you are using the `Nacos` as the `Service Registration & Discovery`, can you tell me more about it? What's the benefit of it? And how do you use it in your system?
#### SubQuestion 8: How To Keep the high available of the `Nacos`? Do you have any idea about it? The `Nacos` is `CP` or `AP`? What's the difference between them?
#### SubQuestion 9: Why you choose the `Snow Flake` as the `ID Generator`? What's the benefit of it? And how do you use it in your system?
#### SubQuestion 10: You mentioned that you are using the `LoadBlancer` to balance the load, can you tell me more about how you use it in your system? What's the benefit of it? Do you know how many types of `LoadBlancer`? And what's the difference between them?
#### SubQuestion 11: The `LoadBlancer` is used to balance the load, it is a kind of `High Availability` solution, do you have any other `High Availability` solution in your system? If yes, can you tell me more about it? If no, why you don't have it? If you have a chance to implement it, how you will do it?
#### SubQuestion 12: Do you know how distributed systems elect their master nodes? How is it done? What are the commonly used methods? Do you know what split-brain is?
#### SubQuestion 13: Do you know the `Service Current Limiting, Downgrading, and Peak-Cutting`, do you understand where the performance bottlenecks of your service are? If once your service is under high load, how you will do to prevent the system from crashing?

### Question 2: I have noticed that you have developed a system named as "音乐播放器," can you tell me more about it?

#### SubQuestion 1: You noticed that you have designed a `Data Sturcture` to store the business data, can you tell me more about how you design it? What's the benefit of it? And how do you use it in your system?
#### SubQuestion 2: Could you tell me what is the `Inverted index` and how you use it in your system? What's the benefit of it? Tell me more about your `Inverted index` implementation?
#### SubQuestion 3: Why you choose the `MongoDB` as the `Data Storage` not the `ElasticSearch`? 
#### SubQuestion 4: The business data will be stored in the `OLTP`? Then How do you keep the data consistency? Do you have any idea about the `CAP`? What's the difference between the `CAP` and the `BASE`?

### Question 3: Please tell me why you try to design this system? I don't see any difference between the above two projects? What are the technical differences between them? (Fatal question)


## Normal Technical Questions

### Question 1: Can you tell me the difference between the `HashMap` and the `ConcurrentHashMap`? What's the benefit of the `ConcurrentHashMap`? And how do you use it in your system?

### Question 2: Do you know the `ThreadLocal`? Can you tell me more about it? What's the benefit of it? And how do you use it in your system?

### Question 3: Do you know how to locate the cause of a certain interface performance? What are the common causes of performance? What is the solution? Briefly describe your thinking?

### Question 4: Do you know about the `MySQL' s Index`? The MySQL contains how many types of index? Please introduce them group by group? And how do you use it in your system? Do you Know the Index failure problem, How do you prevent it?

### Question 5: Do you know what is the `Transaction`? What's the benefit of it? And how do you use it in your system? How do the MySQL implement the `Transaction`? What's the difference between the `InnoDB` and the `MyISAM`?

### Question 6: Do you know about the `Distribution Transaction`? Please tell me more about it?

### Question 7: Do you know about the `RPC` and the `RESTful`? What's the difference between them? And how do you use it in your system?

### Question 8: Do you know about the `Message Queue`? What's the benefit of it? And how do you use it in your system? 

### Question 9: Do you know about the `Cache`? What's the benefit of it? And how do you use it in your system?