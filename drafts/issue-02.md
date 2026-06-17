📱 What I've been reading this week — iOS edition #2

<One-line theme or hook>

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
   TL;DR: <one line>
   My take: <1–2 sentences>

—
Currently: <one line on what you're building / studying>

What are you reading this week? 👇

#iOSDev #Swift #SwiftUI #MobileDevelopment #RemoteWork
