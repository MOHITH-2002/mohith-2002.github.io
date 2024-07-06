**Course Name:** Algorithmic Problem Solving  
**Course Code:** 23ECSE309  
**Name:** Mohith B A  
**SRN:** 01FE21BEC267   
**University:** KLE Technological University, Hubballi-31  
**Portfolio domain:** Disney+ Hotstar   

## Introduction
Disney+ Hotstar is a leading Over-The-Top (OTT) platform known for its extensive content library and live-streaming capabilities, catering to millions of users globally. This portfolio delves into the intricate technological landscape of Disney+ Hotstar, exploring the complexities of content management, real-time streaming, and personalized user experiences. By examining the role of advanced data structures, algorithms, and system design principles, this portfolio aims to uncover innovative solutions that enhance platform performance and user satisfaction.

### Objectives
- Categorize the features and underlying technologies of Disney+ Hotstar.
- Identify the key algorithms, data structures, or system design techniques to enhance the features of Disney+ Hotstar.
- Provide insights into how these technologies optimize platform performance and user experience.

## Journey of the content

Disney+ Hotstar starts by uploading a wide variety of content, such as popular movies, TV shows, and live sports events, to its cloud-based storage systems. Once uploaded, videos undergo careful transcoding and optimization to ensure they can be viewed on different devices and network conditions, improving the streaming quality and user experience. By utilizing a global network of Content Delivery Networks (CDNs), Disney+ Hotstar efficiently distributes cached content to viewers worldwide, reducing delays and optimizing bandwidth for smooth streaming. Advanced streaming protocols like MPEG-DASH adjust streaming quality based on network changes, ensuring uninterrupted playback. Personalized content recommendations, powered by sophisticated algorithms, analyze user preferences and viewing habits, improving engagement and satisfaction. Throughout this process, Disney+ Hotstar is constantly innovating to provide an engaging and personalized entertainment experience, solidifying its position as a leading OTT platform worldwide.


## Business Use Cases


#### 1. Live Streaming Optimization

OTT platforms, such as Disney+ Hotstar, heavily rely on live streaming for events like sports matches and concerts. Efficient handling of real-time data processing and distribution is crucial for ensuring seamless streaming and a high-quality viewer experience.

**Challenges**: Handling high concurrent viewership and ensuring low latency.

**Market Benefits**: Enhanced user engagement and increased viewer retention.

**Design techniques and algorithms:**  
- **Load Balancing:** Round Robin or Least Connections algorithm
- **Real-time Data Processing:** Stream data processing using Kafka Streams

  
[View Implementation](https://www.geeksforgeeks.org/round-robin-scheduling-with-different-arrival-times/)

#### 2. Video Upload Efficiency
Efficiently managing the ingestion and processing of user-generated videos is essential for OTT platforms to maintain a seamless content upload experience.

**Challenges**: Scalability of video upload processes, Efficient resource allocation.

**Market Benefits**: Faster content availability and improved user satisfaction.

**Design techniques and algorithms:**  
-  **Queue Management:** FIFO (First In, First Out) for handling video upload tasks
-  **Dynamic Programming:** Optimizing video transcoding and compression



#### 3. CDN optimization
Content Delivery Networks (CDNs) play a vital role in optimizing content delivery across geographically dispersed regions, ensuring quicker load times, and reducing bandwidth costs.

**Challenges**: CDN costs, Smooth playback for all users.

**Market Benefits**: Reduced latency, Cost savings, Smoother playback.

**Design techniques and algorithms:**  
-  **A * Search Algorithm:** Greedy approach, heuristic-based
-  **Best first search:** Priority queue, BFS


#### 4. Content-Based Filtering: Genre-based recommendation systems
Content-based filtering recommends content to users based on their past interactions and the attributes of the content itself (e.g., genre, keywords, metadata). It creates user-profiles and matches content attributes with user preferences.

**Challenges**: Real-time processing, Data overload.

**Market Benefits**: Personalization, increased user satisfaction.

**Design techniques and algorithms:**  
-  **Collaborative filtering: ALS Algorithm** 

#### 5. Subscription Recommendation Engines

Subscription recommendation engines analyze user behaviour and preferences to suggest the most suitable subscription plans. They utilize predictive algorithms to anticipate potential user disengagement and use this data to maintain user interest.

**Challenges**: Data Accuracy and Availability, Privacy Concerns.

**Market Benefits**: Improved Customer Retention and Increased Revenue

**Design techniques and algorithms:**  
-  **organizing subscriber profiles:** Hashing, Binary Search Trees.
-  **Predictive Models:** Logistic Regression, Decision Trees


### References
- [Disney+ Hotstar System Design for Live Streaming ](https://medium.com/@Gaurav123/disney-hotstar-system-design-for-43-million-concurrent-users-for-india-vs-nz-cwc-2023-262ae9607e0d)

- [Disney+ Hotstar System Design](https://codersguild.github.io/System-Design/Hotstar%20Engineering/)

- [Disney+ Hotstar](https://economictimes.indiatimes.com/industry/media/entertainment/media/disney-hotstar-loses-12-5-million-subscribers-ceo-sheds-light-on-strategic-options-for-tv-business/articleshow/102591418.cms?from=mdr)
