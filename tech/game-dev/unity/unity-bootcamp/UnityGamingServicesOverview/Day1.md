# Glossary
## Live Games
- Multiplayer games
- Games with content updates
- Worlds that persist/etc
- these are very popular

# UGS
## What it provides
- Foundation - Accounts/Multiplayer/Configuration
- Engage - Analytics/Player Engagement/Community Solutions/Monitor Performance
- Grow Game - Monetization/Acquire Users
## Dashboard
- https://dashboard.unity3d.com/
- Project Settings -> Services
  - must link the project to Unity Gaming Services
- Easy to turn on the services in the dashboard
- Economy Configuration
  - can easily change the shop items costs/items/etc and then publish the new configuration
  - can also give custom data
  - Can also check player's information
- Remote Config
  - can quickly rebalance the game/change values without needing the player to redownload
- Analytics
  - Game Performance: based on events (e.g. turn on the game, complete event, etc), prebuilt with KPI's
    - can be exported
  - Retention/Churn Rate/etc
  - Revenue
  - Acquisition
  - Data Explorer - logs
  - Event Manager - can create custom events
  - Event Browser - can debug/investigate events (both valid and invalid events)
## Package Manager
- Authentication: Package Manager -> Unity Registry -> Authentication -> Import
## Multiplayer Stack
- netcode for GameObjects -> Syncronize data across all clients
- lobby -> Create public/private lobbies
- relay -> P2P Connections
- vivox - voice/text chat
- game server hosting - dedi server hosting (unity or unreal or custom engine)
- matchmaker - match right players to deliver gameplay 
## Demos
- Game Lobby Sample - https://github.com/Unity-Technologies/com.unity.services.samples.game-lobby
- Mainframe - scifi collectible card game that showcases Unity Backend gaming solutions, demonstrates multiple UGS (Economy, Cloud Code, Cloud Save, etc)
## Game Backend Solutions
- Authentication - Secure login/player data, Cross platform/cross device
- Cloud Save - store player data, persistant player info
- Cloud Code - server hosted logic, update scripts without any patches/downloads
- Economy - create/manage/publish an economy system for your game, convenient dashboard to manage items/inventories/IAP
- Cloud Content Delivery - deliver right content at right time, cloud storage assets to reduce install size of the game
## Analytics
- pre built dashboards/visualizations
- customizations based on goals with custom audiences/events/flexible reporting
- advanced functionability like SQL Data explorer and Funnels for more flexibility/power
## Monetization and Growth
- Monetize - banner/interstitial ads/reward ads
- Mediation - ad demand from top networks by driving higher yield for your game
- In App Purchases - Enable inapp purchases across multiple stores with a unified API
- Acquire - performance marketer/brand marketer/DSP/etc

# Sources/Useful Links
- https://create.unity.com/ugs-overview-bootcamp
- https://unity.com/solutions/gaming-services 
- https://docs.unity.com/ugs-overview/unity-gaming-services-home.html
- https://forum.unity.com/forums/unity-gaming-services-general-discussion.561/
- Pricing Page https://unity.com/solutions/gaming-services/pricing 
- https://github.com/Unity-Technologies/com.unity.services.samples.use-cases
- https://github.com/Unity-Technologies/com.unity.services.samples.game-lobby
- https://github.com/UnityTechnologies/Mainframe
- https://github.com/Unity-Technologies/com.unity.multiplayer.samples.coop
- https://unity.com/roadmap/unity-gaming-services

# Notes/Future Notes
- web3: Does not do these yet, they are still thinking about it/researching options, but needs it to mature (e.g. it is pointless if it gets implemented and that option is obsolete already)
- client vs server runtime