📱 What I've been reading this week - iOS edition #1

1. Stop using offset as Identity: The Real SwiftUI Lesson behind enumerated() - https://www.linkedin.com/in/foks-huiwang/
   🔗 https://medium.com/@foks.wang/stop-using-offset-as-identity-the-real-swiftui-lesson-behind-enumerated-eca219624fbf
   
   TL;DR: Don't rely on indices or offsets for view identity. Rely on stable view identity
   
   My take: Prefer stable view identity since SwiftUI's diffing model depends on this. Do not prefer offset identity which 
   can produce incorrect animations, stale row state and performance issues.

2. SwiftUI: Observable macro under the hood - https://www.linkedin.com/in/n-vasilev
   🔗 https://www.nsvasilev.com/posts/swiftui-observable-macro/
   
   TL;DR: In the observation framework state object ownership and observation are seperate concerns. @Observable and @
   State removes the need for @StateObject and @ObservableObject. And more granular performant view re-renders are possible
   since SwiftUI integrates and tracks dependencies on specific observable models automatically.
   
   My take: Prefer @Observable when targeting iOS 17+, the observation framework produces a simpler, explicit
   and transparent mental model since state ownshiper and state observation are distinct concepts.This change 
   simplifies the Observation mental model for developers. And more granular performant view re-renders are possible.

3. My Approach to Building Large Technichal Projects
   🔗 https://mitchellh.com/writing/building-large-technical-projects
   
   TL;DR: It is very challenging to start and stay encouraged to complete large projects. However by breaking 
   the project down into small testable chunks which give you a quick feedback loop allows you to feel
   a sense of progress, and positive emotion as you work on big complicated tasks.
   
   My take: The skill of decomposing a problem into sub-problems and quick feedback loops are invaluable. Workflows 
   and development paradigms like TDD can be exceptionally effective if automated tests are fast enough to
   provide good feedback. Also, it is important to consider the sustainablity of our development approach in relation to 
   health, energy, and mental well-being. This is a point Mitchell did not mention but which I believe is important
   to remember. I hoep for all of us consistently succeed over a long period of time)).

—
Currently: studying and exploring AI agents, Web3, and mobile apps system design & architecture.

Comment what are you reading or learning this week? 👇

#iOSDev #Swift #SwiftUI #MobileDevelopment #RemoteWork #AI #Web3 #SystemDesign
#Architecture
