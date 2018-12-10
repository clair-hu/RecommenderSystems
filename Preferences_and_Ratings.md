----
# Preferences and Ratings

## Preference
* Explicit
  * Rating
  * Review
  * Vote
* Implicit
  * Click
  * Purchase
  * Follow

----
# Explicit ratings

## Star Ratings
* Widely-used interface
* Several design decisions
 - 5? 7? 10? stars
 - Half-stars?
 - Provide meaning/calibration? (tool tip)
 - More not necessarily better
* 5, with or without 1/2, very common

## Thumbs and Likes
* Vote up/down
* Or just 'Like'/'+1'
* Common with ephemeral item
 - News aggregation (Reddit, Digg)
 - Q&A (StackOverflow)
 - YouTube
* Very low cost to rate

## Other Interfaces
* Continuous scales
* Pairwise preference
* Hybrid (e.g. 1-100 + never again)
* Temporary (e.g. Pandora 30-day suspend)

## When are ratings provided
* Consumption -- during or immediately after experiencing the item
* Memory -- some time after experience
* Expectation -- the item has not been experienced

## Difficulties with Ratings
* Are ratings reliable and accurate?
* Do user preferences change?
* What does a rating mean?

----
# Implicit ratings
## Implicit data
* Data collected from user actions
* Key difference: user action is for some other purpose, not expressing preference
* Their actions say a lot

## Reading Time
* Early implicit data: how long did user read?
* Listening and watching
 - IMMS
 - Videoservices

## Binary Actions
* Click on link (ad, result, cross-reference)
* Don't click on link
* Purchase
* Follow/Friend

## Subtleties and Difficulties
* What does the action mean?
 - Purchase: they might still hate it
 - Don't click: expect bad, or didn't see
* How to scale/represent actions?
* Lots of opportunity to be creepy
 - Education may help
 - So can respecting privacy

----
 # Conclusion  

 * Recommenders mind both what users *say* and what they *do* to learn preferences

 * Ratings provide explicit expressions of preference

 * Implicit dadta benefits from greater volumne

 Q: Which of the following statements about implicit ratings data are true? (Select all that apply)  
 A:   

	Implicit ratings are usually easier to collect than explicit ratings.

	This should be selected 

	Implicit ratings may come in large quantities, but they’re never individually as meaningful or accurate as explicit ratings.

	This should not be selected 
	In some cases implicit ratings may mean more than explicit ones. A consumer may feel that he or she wants to support certain artists by rating their works highly, but would never actually buy that art for him or herself. The purchased art may be a more accurate reflection of what tastes that consumer really has.


	It is possible to have many different sources of implicit data about preference in the same system.

	Correct 
	That’s right. It is possible to look at time-spent-browsing, clicks, purchases, review text, forwards, and lots of other things all together. The trick is putting those into a formula that provides a combined measure of preference.


	Implicit ratings are always of a yes/no form; you need explicit ratings to judge how much a user likes something.

	Un-selected is correct 