# usvotingevolution

Inspired by several tiktok posts:

https://www.tiktok.com/@dracosweeney/video/7184976232004554027

https://www.tiktok.com/@sparkyissus/video/7177770533516234027

https://www.tiktok.com/@yaoet/video/7167461367841180970

It seems like there's a kiosk in a museum that shows whether you'll be able to vote or not based on what you select.

Supposed to show how election laws have evolved throughout time and they've significantly differed state-to-state (or colonies before revolutionary war) and the years.

Found the concept pretty interesting but I couldn't find a web version for it so I'm trying to recreate it here.
Planning to deploy this on github pages so that's easily viewable by everyone: https://usvotingevolution.github.io/

# Flow
1) Upon opening, a map is shown in which a user can select different states (some states are not shown because they didn't exist then depending on the year that's selected). A default year will need to be selected. 
2) In the museum, there were probably multiple kiosks depending on the year. To replicate this, we need to add an option to select a year directly on this map screen. 
3) Upon choosing a year and then a state, it should load the questions and correct logic to get the proper voting qualifications. 

Year -> State -> Questions 

# Info of what I've gathered so far
## Connecticut (1765)
* Are you white?
    - No -> Continue
* Are you a man?
    - No -> Denied
* Are you over 21 years of age?
    - No -> Denied
* Are you a Citizen?
* Do you own property in this state?
    - No -> Denied
    - "Connecticut required land worth an annual rent of £2 or livestock worth £40."
* Are your taxes paid?
* Can you read and write English?
* Have you been convicted of a crime?
* Have you lived in this state for 1 year?

https://www.crf-usa.org/bill-of-rights-in-action/bria-8-1-b-who-voted-in-early-america
https://research.colonialwilliamsburg.org/Foundation/journal/Spring07/elections.cfm

## Pennsylvania (1870)
* Are you white?
    - No -> Continue
* Are you a man?
    - No -> Denied
* Are you over 21 years of age?
* Are you a Citizen?
* Do you own property in this state?
* Are your taxes paid?
* Can you read and write English?
* Have you been convicted of a crime?
* Have you lived in this state for 1 year?


