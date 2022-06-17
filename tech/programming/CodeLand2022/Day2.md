Opening Comments (Scott Hanselman)
======
## Notes
## Sources

Begin your Developer Journey to Cloud + AI (Nitya Narasimhan)
======
(Microsoft Azure)
## Notes
- Twitter: https://twitter.com/nitya
- Cloud Computing is about delivering computing services over the internet
- outsource management to focus on innovation
- where to start
- Learn Fundamentals 
    - Take a programming language that is relevant to cloud platforms (java/javascript/python/etc)
    - Azure - learn core concepts&services (get certification)
    - Dev Tools - become a power user (VS Code, CLI, CL/CD)
- Build local prototypes
    - Use Frameworks - learn application frameworks for you language
    - Quickstart - build with starter templates, explore open-source
    - Development Environment - Install and use the right tools for e2e workflows
- Deploy to cloud and scale
    - Azure Static Web Apps - build and deploy directly from the codebase
    - Azure Functions - event driven serverless API and architecture
    - Azure CosmosDB - multi model globally distributed NoSQL db
- Simplify your development experience and Automate
    - VS Code IDE - Rich Extensions, Codespaces, Development containers
    - Github Actions - automated build/test/deploy pipelines
    - Playwright - reliable e2e testing, web automation, and reporting
- Keep yourself accountable
    - set a #30days goal
    - make a roadmap
    - capture progress
- Share your learnings with the community
	- Open source your project - help others explore and reuse it
	- Blog your learnings - good reference for you and others
	- Mentor one person - try pair programming on their project
- #30DaysToLearnIt (https://aka.ms/30DaysOfAzure) - Complete a challenge in 30 Days, get discounts on Certification
- SWA Projects (https://aka.ms/msbuild-js-demo) - resume/personal website
- Visit (http://aka.ms/codeland/2022) - Post a comment or tweet @nitya with your #30Days goal, get a customized sketchnote to help accountability
## Sources


Keynote: Ten Commandments of Navigating Code Reviews (Angie Jones)
======
## Notes
- Twitter: https://twitter.com/techgirl1908
- 10 commandments for navigating code reviews
    - Thou shalt not take it personally - some people are just jerks, some people lack the social skills to write a nice message, some are brutally honest, some people have bias, etc.  Fighting each of these individually will probably not be useful. 
    - Thou shalt not marry the code - don't become attached (married) to the code, you can look like you are emotional/defensive
    - Thou shalt consider all feedback - once detached, it becomes easier to hear what the reviewer said
    - Thou shalt articulate your rationale - you don't need to automatically assume the person right, they may be just throwing ideas out there. Consider their suggestion, but articulate why (and post this in the actual post review publically)
    - Thou shalt be willing to compromise - don't get into a heated back and forth exchange, offer to collaborate in person (e.g. whiteboarding)
    - Thou shalt contribute to others' code reviews - if you're always the submitter and not just the reviewer, you look like a junior developer (also allows you to look at other's code and become a stronger programmer)
    - Thou shalt treat submitters how thou wants to be treated - don't need to be a jerk/be petty when they do it (be the bigger person)
    - Thou shalt not be intimidated by the number of comments - e.g. when learning a new language
    - Thou shalt not repeat the same mistakes
    - Thou shalt embrace the nit (nitpickers)
## Sources

Design Systems for Developers (Kathryn Grayson Nanz)
======
Developer Advocate for KendoReact at Progress
## Notes
- Twitter: https://twitter.com/kathryngrayson
- Design systems are for developers too! - improve your understands of how designs/prototypes translate to code
- What is a design system - collection of interconnected visual elements, organized and documented for easy reference
- What is the purpose - Provide visual/language consistency
- Visual consistency between pages/devices - helps when there's multiple developers working on different pages
- Language consistency - everyone speaking the same words to describe the same thing/standardize
- Design tokens - smallest parts of design system - usually correspond directly to css (e.g. border-radius-regular), use these as variables, brand colors/fonts
- Icon Libraries - choesive set of icons
- Component Libraries - collection of all components used in the app and documentation (developer/designer communication)
- Grid Systems - guidelines and structure for page layouts (idea of using a grid to fit information is very old in the design space) (usually UI based). Useful for visual consistency
- Style Guides - downloadable brand assets and documentation (brand colors/fonts), logos/variations, brand specific characters/icons and instructions for their use (consistent look and feel)
- Tone of voice guide - capturing a feeling/tone is hard, but how you do it is very important to the users (small things like buttons/etc can matter a lot) e.g. let's go vs start
## Sources

Women and Tech: Why Representation Matters (Pachi)
======
## Notes
- Twitter: https://twitter.com/pachicodes
- very good tips for allies + good energy
## Sources

Accessibility in Design (Bethany Jepchumba)
======
(Microsoft)
## Notes
- Twitter: https://twitter.com/bethanyjep
- "The power of the Web is in its universality"
- Examples of Disabilities
    - Mobility/motor (might be unable to type)
    - Visual/vision (might be unable to see, color blindness)
    - Cognitive learning/intellectual
    - Auditory/hearing (might be unable to hear)
- Colour Contrast - difference between darkness/light on surfaces (e.g. green and purple) includes text on background
    - contrast of 4.5:1 is advisable for normal text
    - identify contrast via adobe contrast checker (https://color.adobe.com/)
- Colour + additional information to convey meanings
    - colorblind might not be able to see the difference between color
    - e.g. an icon to signify an error
- Alternative text 
    - written image description in place of images
    - useful for people with not as good internet as well
- Transcription (speech to text) - e.g. microsoft word to write from voice
- Practice Empathy 
    - put yourself in your user's shoes

## Sources

Accessibility is Not a Mystery (Laurel Younis)
======
(100Devs)
## Notes
- Twitter: https://twitter.com/LaurelYounisDev 
- Everyone will affect disabilities (even "normal" people) e.g. aging (eyesight/skeletal+muscle/neuro psychological changes/sensory input changes)
- Web Accessability - all users regardless of ability are able to access/use digital tools/websites/etc
- Temporary/Permanent disabilities
- Learning journey for accessibility
- WCAG - (AAA most strict)/AA/A (least strict) standards
    - most websites aim for AA
    - A11y = accessiibility
    - Assistive technology (AT) = devices/software/equipment used to maintain/ehnance funct. capabilities of people with disabilities
- Learning
    - Technical
        - MDN web doc accessibility guide
        - WAI accessibility tutorial (W3C)
        - A11y project
        - Deque University
    - Build empathy
        - get to know users
        - Try using AT
        - User Stories
- Webaim - annual report of most used one million websitesz showing the most common accessibility issues
    - color contrast
    - miss alt text
    - empty links/buttons
    - missing form labels
    - missing lang. attributes
- Color Contrast
    - difference in brightness in foreground/background 4.5:1 ratio
- Missing alt text
    - critical information to provide context
    - Use specific and conscie language
    - describe information conveyed not aesthetics
    - Leave alt text empty for decorative images
- Empty links/Buttons
    - AT's won't read the buttons if it's empty
    - add text content within empty button
    - Add alt text that describes what the button is for/action it triggers
    - purpose of link should be determined by the link text (Read more vs Read more about the company culture)
- Missing form labels
    - make sure every interactive element has a label
    - use html label element
    - use css if you need to hide things from people who can view the content
- Compliance
    - International law (Canada: ACA, AODA) (Europe: EU Web Accessibility Directive)
    - US Law (ADA) (ADA + Section 508) (Unruh Act in California)
- Testing/Tools
    - Automated/Manual, Automated does not catch everything
    - Lighthouse in Google Dev Tools (Automated)
    - Axe dev tool chrome extension (Automated)
    - Screen reader (Manual)
    - Keyboard Access (Manual)
    - User Testing (Manual) as early as possible
- Find community/learn with others/weekly learning challenge (#a11y on twitter/etc)
## Sources

There's More to Open Source than Code (Ramón Huidobro)
======
## Notes
## Sources

Inclusive Web Development (Clifford Ouma)
======
## Notes
## Sources

Speaker Discussion (Ramón Huidobro & Clifford Ouma)
======
(Moderator: Scott Hanselman)
## Notes
## Sources

Speaker Discussion: (Laurel Younis & Pachi)
======
(Moderator: Scott Hanselman)
## Notes
## Sources

Speaker Discussion: Bethany Jepchumba & Kathryn Grayson Nanz
======
(Moderator: Scott Hanselman)
## Notes
## Sources

Automation as Open Source (Jon Peck)
======
## Notes
## Sources

Keynote: Fireside Chat with Tracy Chou
======
## Notes
## Sources

Sources
======
- https://community.codenewbie.org/codeland
- https://www.youtube.com/watch?v=00x40QXsYWA
