<<<tiny
title: Bug Report to SunExpress
style: ../styles/post.css
tiny>>>

[Back to homepage](../index.html)

---

# Bug Report to SunExpress

SunExpress is an airline company that focuses travels between EU countries and Turkiye, a collective brand of Lufthansa and Turkish Airlines. As this airline has a direct flight between my hometown and my current home, it is my first choice to avoid connections.

For the last three years I avoid doing online check-in as SunExpress website sometimes has problems during ticket operations and also passengers do not respect the line separation between check-in and luggage drop causing lots of discussion between checked-in travelers and travelers who are waiting for check-in. This year SunExpress changed its check-in policy and added a penalty fee to the airport check-in, so I decided to go through online check-in.

I had a system problem during the check-in flow and I would like to create a public bug report with timeline, so it might help for the future. All the timeline will be in CEST. As you will see even the customer service agents were not able to resolve the issue.

My configuration for first try: Windows 10 OS, Chrome Browser.

**2023–07–07 14.00** I visited the website, and on the homepage navigated to the Online Check-in tab. After filling in the requested information I was able to se the flight and passenger information. I chose the passengers to check-in and clicked continue, on the further details page I clicked on Continue with login, as the passenger information is saved in my profile. Unfortunately after login website redirected me into the profile page and check-in process is interrupted.

As an already logged in user, I navigated back to home page and started the check-in process from scratch. After filling in the necessary information, website redirected me to profile page again. I tried many times and it kept redirecting to profile page, so I logged out to try again.

Without login, I navigated the home page again and started the check-in once again. Unfortunately this time check-in form kept redirecting me to the login page.

After a few times, I gave up and decided to try again later.

My configuration for second try: Android 11 with MIUI 12.1.1, SunExpress Application version 2.0.10

**2023–07–07 14.30** I tried the mobile application of airline company. I logged into the application, I started the check-in process. I was able to view the flight and passenger details again. But when I filled in the additional details and tried to advance in process, application throw an error message. Unfortunately I did not note down the error message.

Again back to first configuration.

**2023–07–07 21.00** I was more attentive this time. I logged into website, started the check-in process from the main page and landed in the profile page again.

I started an incognito window so the login data would not be stored for other sessions, I logged in, started the check-in process landed in the profile page again.

I started a new incognito window, I did not login and started the check-in process. I was able to see the flight and passenger information, moving to the next page for adding passenger details.

I saw that even the headers for both passengers have correct name, passenger details came with my personal information for both passengers. I changed the second passengers information with the correct ones. And clicked next, accepted the battery and explosive policy then faced an error message about the passenger information. I can translate error message as “Every passenger has its own identity and personal information. Please check the information provided.”

**21.39** I reached out the WhatsApp Customer Service to get help. But the chatbot was not helpful to be honest. At **21.43** a human agent connected to my session to help, I provided the agent with the information at **21.46** and at **21.50** agent informed me that the issue is mitigated and I should refresh the page and try again. And check-in failed again. At **21.58** I said, if the airline will not charge me I can do the check-in at the airport. And the agent confirmed that will be free of charge at **22.00**.

At **22.10** I wrote the things I faced on Twitter where they replied back at **22.23** asking if I still logged in. I informed that I am not. At **22.59** agent requested me to try again on mobile Chrome app without logging in. And share the error message if any. I shared the error message at **23.03**, as a reply agent told me that both passengers have the same passport information and this causes the error. Even though I changed it. And said, if I share passport photos through Twitter DM they can complete the check-in. I refused to share passport photos on DM, and said they can call me to get the information. At **23.32** I have been informed that without visual proof they can not complete the process and the conversation ended.

**2023–07–08 12.55** We approached to the check-in counter in airport. We explained to the agent that we did not have online check-in and she explained that she needs to charge us and we can file a complaint for refund. Then during the process, she said our online check-in was successful and no charge is required.

## Technical Summary

- Website keeps redirecting profile page if user logged in once, redirect continues even after logout.  
- Passenger information details are pulled incorrectly, even though header is correct for the passenger  
- Form does not send the information I filled in, but keeps sending the information pulled when the page is loaded.  

## Conclusion

Even though I had many problems during the online check-in process, I am very happy with the customer service I received. This article aims to serve as a bug report for companies software teams and they can improve the user experience in the future.