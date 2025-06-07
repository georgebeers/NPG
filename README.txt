NPG
===

This is a development log to discuss and document the projects goals, specifications and development as it changes.
Overall, the project is a 2D mobile game consisting of vector graphics, and a focus on intuitive control. 

## 07/06/2025 George
Previously we discussed using flutter + dart to implement the game, but some roadblocks have came up and I'm tentatively moving towards other methods.
The first roadblock was that I did not realise that you need a MacOS dev environment to compile IOS apps. This means I cannot test anything on my device. Nico will have to do all actual testing to there will be a delay on the control implementation, leaving me to just focus on the engine for now. The second issue was that was that I decided to shift away from flutter. I decided that using Kotlin and potentially LibGDK would be more suitable for our purposes, especially as development focuses on android side development (although Kotlin will support IOS with Kotlin Multiplatform). This leaves the current stack being Kotlin + LibGDK. 