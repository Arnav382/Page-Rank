# Page-Rank
PageRank (developed by Larry Page and Sergey Brin) revolutionized web search by generating a ranked list of web pages based on the underlying connectivity of the web. The PageRank algorithm is based on an ideal random web surfer who, when reaching a page, goes to the next page by clicking on a link. 
## How it works
- The algorithm is basically a linear algebra problem where one matrix represents the combination of vectors of a single user's probability of visiting the websites in the internet. Something like this..

![Screenshot 2022-03-18 at 10 01 42 PM](https://user-images.githubusercontent.com/74955631/159043943-d2f89928-2137-4a96-8ab0-0ac206fa1185.png)
- Here each row represents the probability of visiting the websites A,B,C & D.
- Using the concepts of matrix multiplication, eigenvalues, eigenvectors this algorithm computes the score of the websites and returns it 

