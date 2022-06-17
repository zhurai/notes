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
non code contributions to open source
## Notes
- Twitter: https://twitter.com/hola_soy_milk
- Non Code Contributions
- Open Source: Code, Community, Context (where it lives in the outer ecosystem)/Other OSS Projects, etc
- Documentation - README, Development Setup, their website, troubleshooting, fixing typos
- Blogging
- Trying stuff out yourself (e.g. unique setups)
- Issue Triage - if you help mitigate for the maintainers, this can help the developers 
    - Taking issues and assigning tags/assign people/closing duplicate issues
    - some repositories have issue triage guidelines
- Code Reviews/Pull Requests - Asking Questions
- Answering Questions e.g. Stackoverflow
- Meetups
- Hosting hackathons
- Creating Assets
- Giving Talks on Open source projects
- Video Content - above talks, livestreaming
- Website dedicated to the latest resources
## Sources

Inclusive Web Development (Clifford Ouma)
======
## Notes
- Twitter: https://twitter.com/clifford_ouma
- Accessibility/equity/equality/inclusivity
    - accessibility - develop for people w/ various abilities
    - inclusivity - develop. while takin ginto acct. perspective/personal identifiers
    - equality - each individual given the same amount of resources
    - equity - each person is given exact resources req. to reach the same goal
- state of accessibility 
    - ~13% of the world has some form of disability worldwide (~1 billion people) (1/8 people have some form of disability)
    - 50.8 errors per 1 web page (WEBAIM foundation)
    - Complication: self taught developers/online learning -> some key topics (a11y) might not be covered 
- building for the margins 
    - keep traditionally excluded groups top of mind
    - be aware of best case/worst case scenarios
    - building for accessibility is a tide that lifts all ships
- Change priority to be accessible first development from the start (instead of an afterthought)
- How to make the website accessible
    - Follow official guidelines (WCAG and implement guidelines)
    - Avoid common accessibility mistakes (e.g. low contrast, language attr, form labels, empty links, wrong alt text)
    - Automate accessibility tests (lighthouse, wave browser extension, pa11y cli, axe-core cli)
## Sources

Speaker Discussion (Ramón Huidobro & Clifford Ouma)
======
(Moderator: Scott Hanselman)
## Notes
- learning by exposure/putting yourself out there/asking for help
- benefits of being self taught - more resources/democratized resources, learning from other's mistakes
- make a first timer's issue/documentation (example for an intro documentation)
- dealing with impostor syndrome - talking about it is good/everyone has the same feelings/etc
- normalize unconventional path to getting qualified (e.g. some of them are still on their way to a degree/took many years to get the degree)
- don't let an internet stranger ruin your day - block them and move on
## Sources

Speaker Discussion: (Laurel Younis & Pachi)
======
(Moderator: Scott Hanselman)
## Notes
- formalizing raising hand/virtual hand can help give order in conversations (hard to know when someone is done speaking online/virtually, can't see all of the body language)
- important not to exclude other people
- how to recover from excluding the person
    - Saying sorry to the person
    - Ask how they can do better
    - follow the golden rule
    - "Treat others as they want to be treated"
- sponsoring someone else (e.g. their idea) and then stepping aside costs nothing and is good
- learn to be your own best advocate
- be part of the solution, don't be part of the problem
## Sources

Speaker Discussion: Bethany Jepchumba & Kathryn Grayson Nanz
======
(Moderator: Scott Hanselman)
## Notes
- Removing bias - you can absolutely build bias in design systems
- we only have our own lived experience
    - so if we build things based on our own knowledge
    - then you are building in bias into the systems
- Certification isn't everything, you need to do it (you need the experience)
    - e.g. making a site accessible for something local/NGO/churches/etc
    - can learn design this way by making a design system for it/etc
- takeaway: knowledge is good and always useful, but you need to use it/have the experience of using it
- design system beginning -> okay I chose this color for a component, then go save it into a file, then you can compare it later to see if it makes sense
    - incremental
- learn something new every day
- learning design
    - learn enough design to be dangerous
    - The Non-Designer's Design Book (https://www.amazon.com/Non-Designers-Design-Book-4th/dp/0133966151)
    - https://learnui.design/newsletter.html 
    - can also make designs, showing them to other people, getting recommendations/etc and refining
    - "design is a science"
- common thread - intentionality, deliberate practice
- sort list of learning by impact
- "What is the problem I am fixing today"
- look at the accessibility tools and try to use them (put your foot in someone else's shoes)
## Sources

Automation as Open Source (Jon Peck)
======
(GitHub)
## Notes
- Twitter: https://twitter.com/peckjon
- Code + Automation
- CI/CD continous integration/continous deployment: code -> build -> test -> deploy
    - more frequent deployments
    - faster commit to deploy
    - coding everything and then build/test/deploy is very slow and inefficient
- Automate away the boring things (e.g. resize images, check for vuln, retrain ML models, lint new code, etc)
- Github's solution: put it into the repository (Actions Tab in GitHub) -> Automation-as-Code
    - reusable, versionable, reliable
    - decreases failure on deployments
    - faster recovery
- Community powered (programming is a team sport)
    - Actions Marketplace
        - dev tools/frameworks (docker/twilio/gatsby,/etc)
        - ci/cd, test,automation (ansible/mabl, servicenow, jfrog, applitools)
        - monitoring/observability/security (aqua, datadog, lightstep, anchore, veracode)
        - cloud deployments/infra - AWS/Azure, openshift, digitaocean, tencent cloud, hashicorp, etc
## Sources
- https://docs.google.com/presentation/d/1rvYULXN_n9tYhJOZVIKV-O6OxA-o94QwHhR6sf8vFNI/edit
- Actions overview - https://github.com/features/actions
- Actions quickstart - https://docs.github.com/en/actions/quickstart
- Toy Repo: CoreML + GitHub Actions - https://github.com/peckjon/coreml_ghactions

Keynote: Fireside Chat with Tracy Chou
======
Surviving and Thriving as an Idealist In Tech
## Notes
- Twitter: https://twitter.com/triketora
- Twitter: https://twitter.com/bendhalpern
- Inclusion/Systemic Bias 
- "Internalize Success/Externalize Failure" vs "Internalize Failure/Externalize Success"
    - "It's a common thing for women to internalize failure and externalize success, compared to men, who might internalize success and externalize failure"
- 10 years ago (in diversity) vs now (in diversity) - at least talking about it but have not followed through (yet)
- Starting out right now
    - understand that you will have tradeoffs to make
    - you will never have everything perfect
    - can be frustrating when you are compromising
    - Nothing is perfect, pragmatism is good to have
- Healthy Tradeoff vs unhealthy compromise 
    - no easy answer (very contexual/depends on the person)
    - if feeling for too long (maybe 6+ months) that you're unhappy constantly, then reconsider the parameters that need to be changed
    - the amount of time can change in general
- growth can mask a lot of issues
- talk to other people to understand systemic issues (if other people have the same experience as you do, that your experiences aren't unique/etc)
    - be each other's support network
- be ready to learn new skills any time
- getting into tech final words of wisdom 
    - "tech industry needs more idealists to be uncomfortable and to go in new directions"
    - take care of yourself
    - identify what is important (personally)
## Sources

Sources
======
- https://community.codenewbie.org/codeland
- https://www.youtube.com/watch?v=00x40QXsYWA
