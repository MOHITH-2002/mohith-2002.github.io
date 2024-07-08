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


## System Design 

<p align="center">
  <img src="https://files.edgestore.dev/0z6zd9sqa4ndf10i/publicFiles/_public/a5d5d776-dc0e-4811-bb29-55ad5fd27c60.jpeg" width="500" alt="system design">
</p>

## Business Use Cases
#### 1. Live Streaming Optimization
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*05GPe-pAY7iWtPFk8ys3Tw.png" width="500" alt="system design">
</p>
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

#### 3. Load Balancing Across Servers
<p align="center">
  <img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1663170641114/bE6OM6V3k.png?auto=compress,format&format=webp" width="500" alt="Hotstar-load-balancing">
</p>

Load balancing is critical for efficiently managing server resources in large infrastructures like Disney+ Hotstar's live streaming services. It involves distributing incoming traffic across multiple servers to optimize resource use. Effective load balancing ensures high availability and seamless live-streaming experiences for Disney+ Hotstar's global audience.

**Challenges**: Handling sudden traffic spikes and maintaining consistent performance across a global user base.
**Market Benefits**: Enhances user satisfaction and market competitiveness by ensuring seamless streaming experiences.

**Design techniques and algorithms:**  
-  **Dijkstra’s Algorithm:** ShortestPath with non-negative edge weights, minimizing latency and maximizing data transfer efficiency.
-  **Round Robin:** Distributes requests sequentially across the servers.

[View Implementation](https://github.com/MOHITH-2002/java/blob/main/zDDSSAA/Graphs/Dijkshtra.java)
#### 4. CDN Optimization
Content Delivery Networks (CDNs) play a vital role in optimizing content delivery across geographically dispersed regions, ensuring quicker load times, and reducing bandwidth costs.

**Challenges**: CDN costs, Smooth playback for all users.

**Market Benefits**: Reduced latency, Cost savings, Smoother playback.

**Design techniques and algorithms:**  
-  **A * Search Algorithm:** Greedy approach, heuristic-based
-  **Best first search:** Priority queue, BFS
[View Implementation](https://medium.com/@koushiknsec34/ai-a-search-algorithm-in-java-51482ce8f7c3#:~:text=The%20A*%20algorithm%20is%20guaranteed,quality%20of%20the%20heuristic%20function.)

#### 5. Efficient Data Storage in CDNs
CDN servers in Disney+ Hotstar store various data types such as HTML documents, stylesheets, JavaScript files, transcoded video segments, and metadata. Compressing this data using algorithms like Gzip, which combines LZ77 and Huffman coding, ensures efficient storage and faster transmission rates.

**Challenges**: Consider balancing compression ratio and computing costs.
**Market Benefits**:  Cost reduction and Scalablity.

**Design techniques and algorithms:**  
-  **Huffman coding:** lossless data compression algorithm.
[View Implementation](https://www.geeksforgeeks.org/huffman-coding-greedy-algo-3/)
  
#### 6. Content-Based Filtering: Genre-based recommendation systems
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*yZ0Xe4rvSwrt3BRuLKNvKg.png" width="500" alt="content-based">
</p>

Content-based filtering recommends content to users based on their past interactions and the attributes of the content itself (e.g., genre, keywords, metadata). It creates user-profiles and matches content attributes with user preferences.

**Challenges**: Real-time processing, Data overload.

**Market Benefits**: Personalization, increased user satisfaction.

**Design techniques and algorithms:**  
-  **Collaborative filtering: ALS Algorithm** 

#### 7. Subscription Recommendation Engines

Subscription recommendation engines analyze user behaviour and preferences to suggest the most suitable subscription plans. They utilize predictive algorithms to anticipate potential user disengagement and use this data to maintain user interest.

**Challenges**: Data Accuracy and Availability, Privacy Concerns.

**Market Benefits**: Improved Customer Retention and Increased Revenue

**Design techniques and algorithms:**  
-  **organizing subscriber profiles:** Hashing, Binary Search Trees.
-  **Predictive Models:** Logistic Regression, Decision Trees

#### 8. Cross-Device Sync

Disney+ Hotstar's cross-device sync feature enables users to seamlessly continue watching content across multiple devices. For example, a user can start watching a movie on their smart TV, pause it, and then resume from the same point on their smartphone. This feature enhances the user experience by providing continuity and convenience.

**Challenges**: Maintaining consistent data across devices, especially with intermittent connectivity or offline usage.


**Market Benefits**: Users appreciate seamless device switching, leading to higher satisfaction and engagement.

**Design techniques and algorithms:**  
-  **Lazy Propagation:** Delays updates until necessary, reducing data transmission and handling bursts of updates efficiently.
-  **Bloom Filters:** A space-efficient data structure to quickly check if a user has watched a particular show or movie.

#### 9. Search Optimization
<p align="center">
  <img src="https://files.edgestore.dev/0z6zd9sqa4ndf10i/publicFiles/_public/902f0bd8-8d50-4b09-afbe-4d9639e043ee.png" width="500" alt="search-optimization">
</p>

Users often search for longer titles. Autocompleting the next word can enhance the experience. Tries are used to suggest words based on prefixes, and NLP techniques improve accuracy.
**Challenges**: Real-time correction, prediction of user intent, and personalization.
**Market Benefits**: Improved user experience and increased user retention rates.

**Design techniques and algorithms:**  
- **Trie Data Structure:** Greedy approach, heuristic-based

#### 10. Subtitle Synchronization
Subtitle synchronization in Disney+ Hotstar involves aligning subtitle text with audio and visual cues to ensure they appear at the right moment, enhancing the viewing experience for non-native speakers and the hearing impaired.

**Challenges**: Accurate alignment with audio-visual timelines, considering frame rate variations and subtitle file formats.

**Market Benefits**: Improves viewership among non-native speakers and enhances user experience by providing accessible content consumption.

**Design techniques and algorithms:**  
-  **AVL Trees:** Searches traverse the tree based on timestamp values.
  
[View Implementation](https://github.com/MOHITH-2002/java/blob/main/zDDSSAA/Trees/BST/AvlTree.java)
### References
- [Disney+ Hotstar System Design for Live Streaming ](https://medium.com/@Gaurav123/disney-hotstar-system-design-for-43-million-concurrent-users-for-india-vs-nz-cwc-2023-262ae9607e0d)

- [Disney+ Hotstar System Design](https://codersguild.github.io/System-Design/Hotstar%20Engineering/)

- [Disney+ Hotstar](https://economictimes.indiatimes.com/industry/media/entertainment/media/disney-hotstar-loses-12-5-million-subscribers-ceo-sheds-light-on-strategic-options-for-tv-business/articleshow/102591418.cms?from=mdr)
