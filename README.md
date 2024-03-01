# RH-Internship-Projects
This repo documents wireframes/mock-ups I worked on during my time as a SWE Intern at Robert Half/Protiviti 2023-2024
**I am not allow to show exact code from the company repos**

**Some of the General Things I Used:**
- WAMP Stack
- Drupal 
- Double Diamond Methodology 
- Atomic Design System 
- Jira
- Git
- Gitlab
- VSC
- Salesforce

What you'll find... 

# **Mega-menu Redesign**
While doing my best to adhere to company branding (colors, gradients, typography etc.), I needed to increase visibility as per an accessibility, especially since the company's mega-menu had a plethora of information to convey. 

During this project, I conducted research via Double Diamond methodology. I found that ways of increasing visibility included increasing font size, increasing contrast (AAA standards per the company), and changing margins. I used each of these in conjunction and took note of the company's lightning web components via Salesforce to determine efficient means of implementation. I also learned about screen readers, and found especially during this project that aria-labels would be of increasing importance. 

My specific major suggestions were a change in font (you'll notice some screens use Barlow/Barlow Condensed and others use Latto) and the addition of varying shades of sky and navy blue. I also played around with margins and even the removal of entire categories to allow for more 'breathing room'. The rows are repeated at varying resolutions for greater understanding.

https://www.designcouncil.org.uk/our-resources/framework-for-innovation/
https://webflow.com/blog/mega-menu-examples
https://www.lightningdesignsystem.com/guidelines/color/overview/
https://webaim.org/resources/contrastchecker/


# **Podcasts Page Redesign**
This particular project was actually a ticket assignment via Jira during one of my sprints at the company. The ticket made note of the Protiviti 'Podcast' page in which there needed to be some type of UI that displayed the transcript to the audio file provided for users experiencing hearing disabilites. 

I used stylistic notes from the **Mega-menu Redesign** where I used similar colors (sky-blue, navy) and fonts (Barlow/Barlow Condensed, Latto) since I recalled that management and marketing were very fond of them. What I created was a frame for the text to be displayed along with a scroll bar. It was not made known to me exactly how long every audio file would be, so I created the frame to be relatively small in scale. After mocking up a couple frames that were visually appealing, I did some research on the devopment side of things and found the <track> tag in html. One of the attributes of this tag, 'kind', allowed for the addition of the keywords 'caption' and 'description' which provide transcription and textual descriptions respectively. 

If I could change anything about how I handled this ticket, I would have conducted more extensive research into sites with longer audio files and transcripts. I realized that the UI I provided was great for short clips but inefficient for longer ones. 

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/track
https://www.w3.org/WAI/media/av/transcripts/
https://webaim.org/resources/contrastchecker/
https://www.nngroup.com/articles/scrolling-and-scrollbars/

# **Full Homepage Redesign**
This project was worked on along with the **Mega-menu Redesign** and was actually my initial design before then. It was brought to my attention that the company was looking for a way to add more of an aesthetic to the Protiviti Homepage, and so I was tasked with creating a simple mock-up with creative suggestion. I decided that I wanted to add more stylistic appeal to one of the carousels on the page because I wanted to learn more about them as a whole. Carousels are a staple of almost every system (mobile application, website, etc) due to their ability to display media in a condensed format. As such, I spent a looooong amount of time simply viewing carousels and understanding how they are coded. I decided that the current carousels were a bit flat and made it difficult for the user to 'hone' in a single frame. My design choice then was to push the current frame on the carousel to the front by adding a drop shadow and fading the previous and next frames. I thought that this choice would deny the user of the distraction of elements while making the current frame easier to view. 

I did not end up pushing for this to be adopted to the team, but I learned a lot from my research. Looking back on the project, I would have used an opaque color as opposed to a faded white that made things appear a bit too stark. I also think that being unable to view the primary bits of information from the previous and next frames could leave a bit too much to mystery for the user, dissuading them from perusing all that the carousel has to convey. 

https://webaim.org/resources/contrastchecker/
https://raddy.dev/blog/netflix-carousel-using-css/
https://www.smashingmagazine.com/2022/04/designing-better-carousel-ux/
