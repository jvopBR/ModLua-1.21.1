# Minecraft NeoForge Mod — Learning Project (1.21.1)

This repository contains a Minecraft mod developed for **Minecraft 1.21.1** using the **NeoForge** mod loader.  
The primary purpose of this project is **learning**: Java programming, mod architecture, game systems, data-driven development, and integration between code and datapacks.  
There is currently **no defined theme or gameplay goal** for the mod — new features will be added as part of the learning process.

---

## Project Goals

- Learn and practice **Java** in a real, large-scale codebase scenario.
- Understand the **NeoForge modding ecosystem** (registries, events, lifecycle, serialization, networking, etc).
- Explore the structure and interaction between **mods and datapacks**.
- Practice **clean code**, **documentation**, and **commented implementations**.
- Build a maintainable and extensible structure that allows experimenting with new features.
- Apply **GitFlow-inspired branching**, pull requests, and collaborative workflows.

---

##  Project Structure & Standards

### Coding Standards
- All variable names, class names, comments, and file names must be written **in English**.
- Code should follow a **clean, modular, and documented** structure.
- Every class, method, and important logic block should be **commented**.
- Prefer composition over inheritance when possible.
- Follow standard Java conventions:
    - `UpperCamelCase` for classes
    - `lowerCamelCase` for variables and methods
    - `UPPER_SNAKE_CASE` for constants

### Repository Branch Structure

This project uses a simplified GitFlow approach:

`feature/* -> develop -> main`


- **feature/**  
  All new features, fixes, or experiments must be developed in feature branches.
- **develop**  
  Integration branch. Code must pass review before merging.
- **main**  
  Stable, release-ready branch.

### Pull Request Requirements

- PR is required to merge **feature → develop**.
- PR is required to merge **develop → main**.
- Code must be clean, commented, and follow repository conventions.
- PR description must include:
    - Summary of changes
    - Motivation / purpose
    - Checklist (build passes, formatting, manual test if applicable)

---

##  Version & Loader Information

- **Minecraft Version:** 1.21.1
- **Mod Loader:** NeoForge (latest for 1.21.1)
- **Build System:** Gradle
- **Language Level:** Java 21 (JetBrains Runtime 21.0.9)
- **IDE:** IntelliJ IDEA Community Edition

### Why Minecraft 1.21.1?

This version was selected because:

- It has a **large number of existing mods**, which makes integration and study easier.
- NeoForge is stable and well-documented for this version.
- The project may be updated over time to support **new Minecraft releases**, including refactoring when necessary.

---

## Development Setup

### Requirements

- Java 21 (JetBrains Runtime recommended)
- IntelliJ IDEA Community
- Git
- Gradle (wrapper included)
- NeoForge MDK structure

### Running the Dev Environment

1. Clone the repository:
   ```bash
   git clone <repository-url>
    ```
2. Open the project in IntelliJ IDEA
3. Allow Gradle to sync
4. Start the test client
    ```bash
   ./gradlew runClient
    ```
This will launch a **test client**  with the mod loaded

## Project Contents
The project explores and may eventually include:
- Custom blocks and items
- World generation experiments
- Event handling
- Custom registries
- Gameplay mechanics
- UI  experiments
- Data-driven features (datapacks)
- Integration tests
- Logging and debugging tools

Since the purpose is learning, structures will evolve as knowledge grows.

## Contributing
Even though this is a personal learning project, contributions, suggestions, or code reviews are welcome.

### Contribution Rules
- Follow the branch flow: `feature/* -> develop -> main`
- Write all documentation and comments in English
- Keep commits small and descriptive
- Do not push directly to protected branches

## Additional Resources
- NeoForge Documentation
 https://docs.neoforged.net/

- NeoForge Discord
https://discord.neoforged.net/
