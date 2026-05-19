```swift
import Foundation

protocol IOSDeveloper {
    func buildApps()
    var education: [String] { get }
    var careerJourney: [CareerStep] { get }
    var stack: [Tech] { get }
    var tools: [Tool] { get }
}

struct CareerStep {
    let company: String
    let period: String
    let focus: String
}

// MARK: - Type-safe tech representation

enum Tech: String, CaseIterable {
    case swift = "Swift"
    case swiftUI = "SwiftUI"
    case uiKit = "UIKit"
    case combine = "Combine"
    case asyncAwait = "Async/Await"
}

enum Tool: CaseIterable {
    case firebase
    case adapty
    case amplitude
    case appsFlyer
    case restAPI
    case xcuiTests
    case spm
    case git
}

// MARK: - IOSDeveloper Impl

final class SiarheiRamaniuk: IOSDeveloper {
    
    let basedIn = "Poland"
    let stack: [Tech] = Tech.allCases
    let tools: [Tool] = Tool.allCases
    
    private(set) var education: [String] = [
        "Bachelor's degree in Process Engineering of Nano- and Micro-Systems, Belarusian National Technical University, 2012",
        "Course 'SwiftUI Fundamentals', 2023",
        "Coursera 'Meta iOS Developer', 2023"
    ]
    
    private(set) var careerJourney: [CareerStep] = [
        .init(
            company: "ROCK & APPS",
            period: "2025 – Present",
            focus: "Building utility-focused iOS apps for international audiences, experimenting with monetization flows, analytics, and scalable architectures."
        ),
        .init(
            company: "Killing Kittens",
            period: "2024 – 2025",
            focus: "Worked on social and event-related features, improved user engagement, and helped evolve the app’s UI ecosystem."
        ),
        .init(
            company: "Streetcode",
            period: "2023 – 2025",
            focus: "Contributed to a volunteer-driven historical project by developing MVP features and interactive mobile experiences."
        )
    ]
    
    // MARK: - Public

    public func buildApps() {
        careAboutDetails()
        solveRealProblems()
        makeThingsFeelSimple()
        shipToUsers()
    }

    // MARK: - Private
    
    private func careAboutDetails() {
        /// people notice the feeling, even if they don't notice the UI
    }

    private func solveRealProblems() {
        /// product-driven > feature-driven
    }

    private func makeThingsFeelSimple() {
        /// complexity belongs behind the screen
    }

    private func shipToUsers() {
        /// real users are the best architecture review
    }
}

private extension SiarheiRamaniuk {
    var currentlyLearning: [String] {
        [
            "AI-assisted engineering workflows",
            "Advanced iOS architecture patterns",
            "Scalable application design",
        ]
    }

    
    var goals2026: [String] {
        [
            "AI-assisted development workflows",
            "Deepen expertise in mobile architecture",
            "Master Swift Concurrency and reactive programming",
            "Grow as a product-oriented iOS engineer"
        ]
    }

    var hobbies: [String] {
        [
            "Hiking",
            "Extreme sports",
            "DIY Crafting",
            "Tech Innovations",
            "Learning"
        ]
    }
}
```

<!--
**tipe56/tipe56** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
