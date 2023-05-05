Download Link: https://assignmentchef.com/product/solved-cse225-project-2-ranking-documents-for-information-retrieval-with-priority-queues
<br>
In WWW, when you enter a “keyword” search engines try to rank the documents according to the similarities between your keyword and the documents lying on WWW. The most famous search engines are Google, Bing, Yahoo… Various machine learning and deep learning algorithms run behind these search engines. On the other hand, the common logic behind them is to rank the documents according to relevance.

In text classification studies, textual materials are represented with the frequencies of the words. Consider the following three documents:

<strong>Doc1:</strong> “<em>Text mining studies have gained importance in recent years because of the increasing number of electronic documents like news, social networks, research papers and digital libraries. There is no doubt that this enormous data continues to increase day by day with the contribution of lots of people.</em>”

<strong>Doc2:</strong> “<em>Automatically processing, organizing and handling this text materials are a central problem. The key aim of text mining is to allow users to get information from text materials. Text mining mainly deals with several important applications like information retrieval (IR), classification (i.e., supervised, unsupervised and semi supervised classification), document filtering, summarization, sentiment or opinion classification.</em>”

<strong>Doc3:</strong> “<em>Natural Language Processing (NLP), Machine Learning (ML) and Data Mining methods work together to detect patterns from the different types of the documents and classify them in an automatic manner.</em>”




When we want to rank documents according to some keyword there are some different methods in the literature. One of the simplest ways of achieving this task is to find a similarity score between the search keyword and the document by using common terms. For example, let’s calculate the similarity score between the search keyword (i.e., text) and three documents.

<strong><em>Similarity score between search keyword: “text” and Doc1: </em></strong>1 since “text” occurs 1 times in Doc1.

<strong><em>Similarity score between search keyword: “text” and Doc2:</em></strong> 4 since “text” occurs 4 times in Doc2.

<strong><em>Similarity score between search keyword: “text” and Doc3:</em></strong> 0 since “text” occurs 0 times in Doc3.

The most relevant document with the given keyword is the one having the highest similarity score. Consequently, the ranking of the documents according to the relevance to the keyword is <em>Doc2, Doc1, Doc3</em>.




In this project, you are to use binomial heaps to implement a priority queue for the task of ranking documents. In other words, you need to rank documents according to given keyword with binomial heaps.

In the folder of files, there are 42 documents.

Steps:

<ol>

 <li>Open the folder and read the files.</li>

 <li>Ask the user for the keyword and pass it to your program as the keyword parameter</li>

 <li>Decide your heap structure whether you choose max-heap or min-heap.</li>

 <li>Build a priority queue with the keyword.</li>

 <li>By using your priority queue data structures in (d), extract the relevant 5 documents with the keyword.</li>

 <li>Discuss your results in (e) and advantages using priority queue for such a problem.</li>

</ol>

<strong>OUTPUT OF THE REPORT: </strong>

<ul>

 <li>(10 points) Screen shot that you are taking the keyword from the user.</li>

 <li>(5 points) Screen shot that you are taking the NUMBER OF RELEVANT</li>

</ul>

DOCUMENTS.

<ul>

 <li>(25 points)Put your enqueue and dequeue implementation here (Just copy them from your source code) This part needs to be you own study. Taking the implementation from web will not be accepted.</li>

 <li>(50 points)Print your results in (e). The format will be:</li>

</ul>

Assume that the keyword is text and the NUMBER OF RELEVANT DOCUMENTS is 2.




<em>The relevance order is: Doc2(4), Doc1(1)</em>.

<em>Doc2(4): Automatically processing, organizing and handling this text materials are a central problem. The key aim of text mining is to allow users to get information from text materials. Text mining mainly deals with several important applications like information retrieval (IR), classification (i.e., supervised, unsupervised and semi supervised classification), document filtering, summarization, sentiment or opinion classification.</em>”

<em>Doc1(1): Text mining studies have gained importance in recent years because of the increasing number of electronic documents like news, social networks, research papers and digital libraries. There is no doubt that this enormous data continues to increase day by day with the contribution of lots of people </em>

<em>5.) </em>(10 points)<em>Your discussions about the advantages of </em>using priority queue for such a problem.

<strong>VERY IMPORTANT </strong>

<strong>The main goal of this project is to be familiar with </strong>priority queue<strong>. So, use of arrays/linked lists instead of </strong>priority queue <strong>is not acceptable for this project. </strong>

In this project, you are expected to develop an algorithm that is capable of finding a solution to the above problem and <strong><em>implement this algorithm in ANSI C that runs under either UNIX or Windows</em></strong>.


