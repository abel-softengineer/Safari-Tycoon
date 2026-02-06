🦁 Safari Tycoon – 2D Park Simulator
<img width="1913" height="960" alt="image" src="https://github.com/user-attachments/assets/ab34298c-0185-435e-9b56-4ddc750452cc" />


Safari Tycoon is a real-time tycoon game built with Java and the LibGDX framework. The project focuses on complex game engine logic, automated quality assurance, and agile development methodologies.
🎮 Overview

Players take on the role of a park director managing an African safari. The goal is to build a sustainable ecosystem by planting flora, introducing wildlife, and managing infrastructure (roads, jeeps) to satisfy visiting tourists.

<img width="1913" height="1010" alt="image" src="https://github.com/user-attachments/assets/a7825bd1-01d0-40d6-b00f-5c52f93a5895" />

		
Please replace the placeholders with your actual screenshot paths.		
🚀 Advanced Features

Beyond the core mechanics, the following modules were implemented to increase technical complexity:

    🗺️ Minimap: Navigation system for a game world significantly larger than the viewport.

    🌙 Day/Night Cycle: Dynamic lighting system. At night, a "Fog of War" effect limits visibility to the surrounding areas of built infrastructure.

    🏹 Poachers: Hostile entities that attempt to kill or capture the park's wildlife for profit.

    🛡️ Park Rangers: Specialized units tasked with protecting animals from poachers and managing predator populations.

🛠️ Tech Stack & Architecture

    Language: Java (OpenJDK 17+).

    Framework: LibGDX with LWJGL3 backend.

    Build Tool: Gradle.

    CI/CD: Automated Unit testing integrated into a GitLab CI pipeline.

    Management: Agile workflow using Issue boards, Merge Requests, and a structured branching strategy.

<img width="1913" height="1010" alt="image" src="https://github.com/user-attachments/assets/8af9e496-3b37-4b97-9ec0-5a7d75629639" />

<img width="1920" height="1004" alt="image" src="https://github.com/user-attachments/assets/d36ceb18-50af-4826-8ceb-0887b0eda41b" />

💻 How to Run

To run the game locally, ensure you have Java 17 or higher installed.

    Clone the repository:
    Bash

    git clone https://github.com/abel-softengineer/Szafari-LibGDX.git

    Launch via Gradle:
    Bash

    ./gradlew lwjgl3:run

