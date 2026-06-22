📱 What I've been reading this week — iOS edition #2

1. SwiftUI’s @State is now a macro
   🔗 https://livsycode.com/swiftui/swiftuis-state-is-now-a-macro/
   TL;DR: @State marked dependencies are now lazily initialised once for the lifetime of a View.
   Before @State was a property wrapper, and @State marked value inits were called on every view value creation. This meant expensive or side-effectual inits could cause unexpected behaviour in your App. The macro implementation eliminates this problem.
   My take: Changing from a property wrapper to a Macro is not interesting. But The payoff is huge - A host of unwanted @State init bugs are gone. So Apple has improved the behaviour of SwiftUI's state managment system. Its also clear prefer inexpensive inits for your @State dependencies, and ensure your dependencies do not have any unwanted side-effects.

2. ContentUnavailableView in SwiftUI - Complete Guide With Examples
   🔗 https://www.sagarunagar.com/blog/contentunavailableview-swiftui/
   TL;DR: ContentUnavailableView (iOS17+) is the canonical example of the empty state. For a polished, platform consistent empty state with good accessibility out of the box, prefer ContentUnavailableView. If you require brand specific or the empty state is complex (e.g in an interactive tutorial), prefer custom empty states.
   My take: Empty states drive user behaviour and perception. A user must know when something goes wrong, and what to do. Also they should feel good while in your app. This is a real product problem which ContentUnavailableView solves. Before time sunk creating empty states from scracth. Now empty states are declarative primitive in SwiftUI. Zero friction. It is now even easier to create beautiful, accessible, and memorable products on Apple devices with SwiftUI. Our users will smile. And businesses will see sustained revenue with their mobile products. Huge win.
   
3. Using Claude with Apple Foundation Models
   🔗 https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models
   TL;DR: Foundation Models is becoming a univeral interface for language models on Apple platforms. This framework makes it easy to dynamically switch between models, intercept tool calls, and a whole a lot more. Artem Novichkov shows us how east it is to do this using Claude with foundation models.
   My take: This is exciting for developers. We can roll your own server side language model and integrate it our app. On the server: web search, code execution, frontier model calls e.t.c. For the users: the choice between privacy and power. We can switch between on-device and frontier models. So for businesses AI powered mobile experiences are easier than ever to build for your products. This tech opens opportunites for delighting customers. Look for opportunities to do so in your mobile apps.

—
Currently: studying and exploring AI agents, Web3, and mobile apps system design & architecture.

What are you reading this week? 👇

#iOSDev #iOS #Swift #SwiftUI #MobileDevelopment #RemoteWork #AI #Web3 #WWDC2026 #SystemDesign #Architecture
