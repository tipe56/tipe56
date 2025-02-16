```swift
import Foundation

struct DeveloperProfile {
    let name: String
    let locatedIn: String
    let currentJob: String
    let company: String
    let education: [String]
    let fieldsOfInterests: [String]
    let currentlyLearning: [String]
    let goals2025: [String]
    let hobbies: [String]
}

let siarheiRamaniuk = DeveloperProfile(
    name: "Siarhei Ramaniuk",
    locatedIn: "Poland",
    currentJob: "iOS Developer",
    company: "Killing Kittens. London, UK",
    education: [
        "Bachelor's degree in Process Engineering of Nano- and Micro-Systems, Belarusian National Technical University, 2012",
        "Course 'SwiftUI Fundamentals', 2023",
        "Coursera 'Meta iOS Developer', 2023"
    ],
    fieldsOfInterests: [
        "iOS Development",
        "SwiftUI",
        "Mobile App Design",
        "Software Engineering"
    ],
    currentlyLearning: [
        "Advanced SwiftUI techniques",
        "Testing and Debugging in iOS",
        "Architecture Design Patterns"
    ],
    goals2025: [
        "Architecture Design Patterns",
        "Continue work on personal iOS project",
        "Master Swift Concurrency and Combine framework"
    ],
    hobbies: [
        "Hiking", 
        "Extreme sports",
        "DIY Crafting", 
        "Tech Innovations", 
        "Learning"
    ]
)

// Example of accessing the data
print("Name: \(siarheiRamaniuk.name)")
print("Current Job: \(siarheiRamaniuk.currentJob)")
print("Hobbies: \(siarheiRamaniuk.hobbies.joined(separator: ", "))")
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
