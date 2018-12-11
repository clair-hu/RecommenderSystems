# Tour of Amazon

----
## Dimensions of Analysis
* Domain - Products already purchased
* Purpose - To get me to re-buy
* Recommendation Context - General browsing
* Whose Opinions - My implicit purchase data
* Personalization Level - personalized (one product at a time)
* Privacy and Trustworthiness
* Interfaces - clustered suggestions
* Recommendation Algorithms 
 - commonly depleted (Things you use up and get more of)
 - Profitable
 - Purchase cycle

Q: before I go through this example, see how much of the analysis you can do. For “people who bought this pen also bought …” what can you say about the domain, purpose, context, whose opinions, personalization level, privacy/trustworthiness, interfaces, and algorithms? 
 
My Answer:  
domain - products already purchased
purpose - to get people to re-buy
context - N/A
whose opinions - people's implicit purchase data
personalization level - people(a group of people)
interfaces - N/A
algorithm - N/A

Solution:  

* Domain - Products already purchased
* Purpose - add-on sales
* Recommendation Context - Shopping for a product
* Whose Opinions - Other shoppers who bought it
* Personalization Level - epheneral (current product)
* Privacy and Trustworthiness
* Interfaces - set of recommendations
* Recommendation Algorithms - product association

For "Items I've purchased" Improvement on Recommendation: 

* Domain - Products already purchased
* Purpose - ageneral recommendations to purchase
* Recommendation Context - as requested
* Whose Opinions - Other customers + me
* Personalization Level - Personalized to my full history - Edit history (I can mark something as a gift and it stops assuming I would like it. I can rate stars on items I purchased.
* Privacy and Trustworthiness
* Interfaces - list of recommendations
* Recommendation Algorithms 
 - collaborative
 - (maybe?) content based filtering


----
## Which type of recommender appears in Amazon.com?
* Non-personalized summary statistics.
* Ephemeral personalization based on current navigation.
* Persistent personalization based on preferences/behavior.
* All of the above.
 - CORRECT. This is the best answer. All of the above, and more (e.g., demographic personalization)