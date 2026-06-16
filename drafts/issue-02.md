📱 What I've been reading this week — iOS edition #2

<One-line theme or hook>

1. SwiftUI’s @State is now a macro
   🔗 https://livsycode.com/swiftui/swiftuis-state-is-now-a-macro/
   TL;DR: @State marked dependencies are now lazily initialised once for the lifetime of a View.
   Before @State was a property wrapper, and @State marked value inits were called on every view value creation. This meant expensive or side-effectual inits could cause unexpected behaviour in your App. The macro implementation eliminates this problem.
   My take: Changing from a property wrapper to a Macro is not interesting. But The payoff is huge - A host of unwanted @State init bugs are gone. So Apple has improved the behaviour of SwiftUI's state managment system. Its also clear prefer inexpensive inits for your @State dependencies, and ensure your dependencies do not have any unwanted side-effects.

2. ContentUnavailableView in SwiftUI - Complete Guide With Examples
   🔗 https://www.sagarunagar.com/blog/contentunavailableview-swiftui/
   TL;DR: 
   - Production ready examples
   - For native thoughtful UI/UX expereince opt for coneten unavailble view
   - For more branded empty states you are better off writing your own
   My take: Prefer ContentUnavailableView as your standard choice for empty state implementations which do not require heavy brand driven designs. Apple is providing API's and expereince with excpetional product thinking and UI/UX experience out of the box. The tools are there to delight users and customers without a lot of effort

3. Using Claude with Apple Foundation Models
   🔗 https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models
   TL;DR: <one line>
   My take: <1–2 sentences>

—
Currently: <one line on what you're building / studying>

What are you reading this week? 👇

#iOSDev #Swift #SwiftUI #MobileDevelopment #RemoteWork
