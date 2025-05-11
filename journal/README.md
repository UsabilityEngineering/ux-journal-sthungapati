# Appointment Booking Experience with Zocdoc


By Ramani Thungapati

Initial- 14th March, 2025
Edited - 10th May, 2025

**Introduction**

Zocdoc is a platform designed to simplify the process of booking healthcare appointments by allowing users to search based on location, insurance, and provider preferences. While the interface appears clean and modern, my recent experience booking a dental appointment revealed multiple usability issues that hinder both efficiency and trust. What should have been a simple, goal-driven task was slowed down by poor location handling, limited filtering, lack of information architecture, and insufficient transparency.

**The Interaction**

I began by searching for a dentist in Chico, CA, entering my insurance information, and using the app’s available filters. The initial search seemed successful: results appeared quickly, and providers showed multiple open time slots. However, upon closer inspection, the experience began to break down in several ways.

1. Irrelevant Search Results- Despite specifying a clear geographic constraint, the app returned providers located over 40 miles away in cities like Yuba City, as shown in the picture below. This violates the match between system and real-world expectations—users expect location-based queries to honor geographic relevance. The absence of a configurable distance radius or warning about expanded search results led to immediate confusion and undermined the credibility of the results.
![image](https://github.com/user-attachments/assets/cea7eba9-28cc-47ae-a37c-251ee9631ce8)

2. Filtering Constraints: After the unexpected search results, I attempted to narrow down providers using Zocdoc’s filter options. The app does include filters for gender, languages spoken, appointment type, and time of day. However, the filtering system lacks flexibility and task-oriented depth. There are no filters for clinic type, service categories, etc. This limits the system’s ability to support user control and personalization, both essential heuristics in usability engineering.
![image](https://github.com/user-attachments/assets/5edce1fb-c8e6-49e5-87d5-80ec71c11fdd)
   
3. Inadequate Provider Context: As I continued to just check on the listings it gave, I noticed each listing presented minimal information, including the doctor's name, photo, address, and available time slots. There was no mention of clinic affiliation, contact information, or provider credentials. This lack of information violates the principle of visibility of system status and places an unnecessary cognitive load on users, who must click into each profile to gather basic decision-making details.
![image](https://github.com/user-attachments/assets/107dee92-7c7a-44de-90fe-403d6c30b0a1)

4. Lack of Cost and Insurance Transparency: Lastly, Zocdoc includes a subtle “See if they’re in network” link, but it redirects users to an external insurance provider site, breaking the task flow. Additionally, there is no clear display of estimated costs, out-of-network fees, or consultation charges within the booking interface. This omission conflicts with the usability heuristic of visibility of system status, leaving users uncertain about financial obligations and increasing the likelihood of booking errors.


**User Experience Analysis**

Zocdoc’s interface falls short in several core usability areas. When I searched for providers in “Chico, CA,” the app returned results over 40 miles away, breaking my **mental model** of how location-based search should function. There was no feedback or explanation, leaving me unsure whether the app was working as intended.
The platform also fails to provide meaningful **feedback** during booking. Insurance network status and cost estimates are hidden behind external links or not shown at all. Without this information, users can’t make informed decisions and are more likely to make mistakes, highlighting a lack of **error prevention**.
While Zocdoc includes basic filters, they are too limited to support diverse user needs, reducing **user control**. The provider listings also lack critical context like clinic names or qualifications, which forces extra navigation and slows the process. This negatively affects the app’s overall **efficiency**, making a simple task more tedious than it should be.

Overall, the experience feels incomplete: users are given tools to search, but not enough clarity to decide. Improving visibility, aligning system behavior with expectations, and minimizing redundant steps would significantly enhance the platform’s usability.


**Suggestions for Improvement**

To improve the user experience, Zocdoc could implement the following changes:
**Improve Location Logic**: Enforce tighter geolocation constraints or allow users to manually set a distance radius (e.g., 10–25 miles).
**Expand Filter Set**: Include clinic type, accepted insurance tiers, and specialty procedures to support more refined decision-making.
**Enhance Provider Previews**: Add clinic names, contact details, and core qualifications to reduce information-seeking friction.
**Display Cost Information**: Clearly show estimated fees, network status, and any deposits before finalizing appointments.

**Conclusion**

While Zocdoc offers valuable functionality, its current design suffers from poor geographic accuracy, underpowered filters, incomplete provider information, and opaque cost structures. These issues reduce the system’s overall usability, especially for users trying to make quick, informed decisions under pressure. A more user-centered approach—one grounded in established usability principles—would significantly improve both the efficiency and trustworthiness of the platform.
