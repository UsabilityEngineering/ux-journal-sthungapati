# Appointment Booking Experience with Zocdoc


By Ramani Thungapati

Initial- 14th March, 2025

Edited - 10th May, 2025

**Introduction**

Zocdoc is a platform designed to simplify the process of booking healthcare appointments by allowing users to search based on location, insurance, and provider preferences. While the interface appears clean and modern, my recent experience booking a dental appointment revealed multiple usability issues that hinder both efficiency and trust. What should have been a simple, goal-driven task was slowed down by poor location handling, limited filtering, lack of information architecture, and insufficient transparency.

**The Interaction**

I began by searching for a dentist in Chico, CA, entering my insurance information, and using the app’s available filters. The initial search seemed successful: results appeared quickly, and providers showed multiple open time slots. However, upon closer inspection, the experience began to break down in several ways.
The most immediate issue was the irrelevant search results. Although I had clearly set the location to Chico, the app displayed providers located over 40 miles away, including several in cities like Yuba City as shown in the picture below. This broke my **mental model** of what a location-based search should return. Users expect a search tied to a city to stay within a reasonable distance, and there was no feedback or alert to suggest the app had expanded the search range.

![image](https://github.com/user-attachments/assets/cea7eba9-28cc-47ae-a37c-251ee9631ce8)

Hoping to narrow the list, I explored Zocdoc’s filters. The app offers a few useful options, such as doctor gender, languages spoken, appointment type, and time of day. However, these filters are too limited to fully support user control and personalization. There were no options to filter by clinic type, specific services, or insurance tiers, making it difficult to tailor the results to my actual needs.

![image](https://github.com/user-attachments/assets/5edce1fb-c8e6-49e5-87d5-80ec71c11fdd)

As I reviewed individual provider listings, I noticed a consistent lack of detail. Each result included only the doctor’s name, photo, address, and a few time slots. There was no mention of clinic affiliation, contact information, or provider credentials. This omission violated the principle of visibility of system status and forced me to click into each profile just to find basic information—adding unnecessary steps and cognitive load to the process.   

![image](https://github.com/user-attachments/assets/107dee92-7c7a-44de-90fe-403d6c30b0a1)

The final issue came during booking. While some listings included a link labeled “See if they’re in network,” clicking it redirected me to an external insurance site. There was no integrated feedback on cost estimates, out-of-network charges, or consultation fees. Without clear information upfront, users are more likely to experience confusion or make decisions they later regret. This violates both **feedback** and **error prevention**, two essential heuristics in usable system design.


**User Experience Analysis**

Zocdoc’s surface design is polished, but several underlying usability flaws impact task success and decision-making. When the app returned providers far outside the specified location, it broke the expected logic of search and created immediate doubt in the system. This disconnect between input and output reflects a failure to maintain system–real world alignment.

The lack of meaningful **feedback** during booking—particularly around insurance coverage and pricing—leaves users in the dark. Information critical to decision-making is either buried or missing, increasing uncertainty and risk.

While Zocdoc includes some filters, their limited scope undermines **user control**. Users cannot fully customize the search to reflect personal or practical preferences. The sparse provider previews also slow down the process, requiring repetitive navigation and reducing **efficiency of use**.

Finally, Zocdoc does little to prevent errors before they occur. With no alerts about missing price details or out-of-network risks, users are forced to proceed with incomplete information, violating principles of error prevention and task support.


**Suggestions for Improvement**

Zocdoc could significantly improve its user experience by aligning with established usability heuristics:
- It should offer clearer location feedback and enforce tighter geolocation boundaries, or allow users to define their own distance range.
- The filter system should be expanded to include clinic type, insurance tiers, and specific services, improving relevance and task control.
- Provider previews should include contact information, qualifications, and clinic names, reducing the need for unnecessary clicks.
- Finally, the app must surface estimated costs, insurance compatibility, and any consultation fees directly within the appointment flow to support informed, confident decision-making.


**Conclusion**

Zocdoc provides a helpful platform for healthcare booking, but several key usability issues reduce its overall effectiveness. By overlooking foundational principles like **feedback**, **user control**, **efficiency**, and **error prevention**, the app creates friction in an experience where users value clarity and speed. With targeted improvements in information visibility and interaction design, Zocdoc has the potential to offer a truly reliable and user-centered healthcare experience.
