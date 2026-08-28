# 🚀 SuperProject

> A free, lightning-fast project management platform built to turn plain text into a complete project workspace in seconds.

![License](https://img.shields.io/badge/license-Free-brightgreen)
![Single File](https://img.shields.io/badge/architecture-single--file-blue)
![HTML](https://img.shields.io/badge/HTML-index.html-orange)

**SuperProject** is a completely free project management platform designed for speed, simplicity, and flexibility.

The entire application runs from a **single `index.html` file**. No installation, no backend setup, no complicated configuration and no paid subscription required.

The main idea is simple:

Instead of clicking **“Add Task”** 150 times, you can ask an AI to structure your project, paste the generated text into SuperProject, and 💥 **instantly generate an entire organized workspace**.

---

## ✨ The Magic

Create your project structure using simple text:

```text
Initial Setup - Install Node.js - Install Expo
Frontend - Create Login Screen - Create Home Screen
Backend - Create API - Configure Database
```

Paste it into SuperProject.

The result:

```text
📁 Initial Setup
   ☐ Install Node.js
   ☐ Install Expo

📁 Frontend
   ☐ Create Login Screen
   ☐ Create Home Screen

📁 Backend
   ☐ Create API
   ☐ Configure Database
```

Each line becomes a new project page.

Each item after the first separator becomes a task.

You can import **hundreds of tasks at once**.

---

# ⚡ Why SuperProject?

Traditional project management tools can be slow to set up.

You create a project.

Then a page.

Then another page.

Then a task.

Then another task.

Then subtasks.

Then deadlines.

Then phases.

SuperProject takes a different approach.

### 🤖 AI generates the structure.

### 📋 You paste the text.

### 💥 The project is created instantly.

SuperProject is especially useful for:

* 🚀 Software projects
* 🎨 Design projects
* 📚 Study plans
* 🏢 Business planning
* 📱 Product roadmaps
* 🧠 Personal projects
* 📝 Content planning
* 🎯 OKR planning
* 👥 Team projects

---

# 🧠 How to Create a Project

Write **one line for each page**.

Use hyphens (`-`) to separate the page name from its tasks.

```text
Page - Task 1 - Task 2 - Task 3
```

### Example

```text
Initial Setup - Install Node.js - Install Expo
Frontend - Create Login - Create Home
Backend - Create API - Configure Database
```

### Result

```text
📁 Initial Setup
   ☐ Install Node.js
   ☐ Install Expo

📁 Frontend
   ☐ Create Login
   ☐ Create Home

📁 Backend
   ☐ Create API
   ☐ Configure Database
```

---

# 📌 Import Rules

SuperProject follows a very simple syntax:

### 1. The first text becomes the page name

```text
Frontend - Create Login - Create Home
```

📁 Page:

```text
Frontend
```

---

### 2. Everything after the hyphen becomes a task

```text
Frontend - Create Login - Create Home
```

Tasks:

```text
☐ Create Login
☐ Create Home
```

---

### 3. Each line creates a new page

```text
Frontend - Create Login
Backend - Create API
Database - Configure PostgreSQL
```

Creates:

```text
📁 Frontend
📁 Backend
📁 Database
```

---

### 4. Import hundreds of tasks at once

You can generate a complete project structure with an AI and paste everything directly into SuperProject.

Example prompt:

> Create a complete project structure for a mobile application. Format each line as: Page - Task 1 - Task 2 - Task 3.

Then copy the AI response and import it.

---

# 💾 Save and Import

SuperProject supports different formats depending on what you need.

## TXT

Saving as **TXT** generates the project using the same simple text format.

Example:

```text
Frontend - Create Login - Create Home
Backend - Create API
```

Perfect for:

* Quick backups
* AI generation
* Editing in any text editor
* Sharing simple project structures

---

## JSON

Saving as **JSON** stores the complete project data.

This includes:

* Phases
* Types
* Deadlines
* Details
* OKRs
* Project structure

JSON is the best option for a complete backup.

---

## Import

SuperProject accepts:

* 📄 TXT files
* 🧩 JSON files
* ✍️ Freshly written text

---

# 👀 Project Views

Visualize your project in different ways.

## 📋 List

The classic checklist view.

Perfect for:

* Simple task management
* Daily planning
* Quick overviews

---

## 🖼️ Frames

Tasks are displayed as side-by-side cards.

Perfect for:

* Visual organization
* High-level project overview
* Grouping related work

---

## 📌 Kanban

Organize tasks into columns based on their phase or progress.

Drag and move items between stages.

Perfect for:

* Workflow management
* Team processes
* Visual task tracking

---

## 🏃 Sprint

Each phase has its own progress.

Perfect for:

* Agile workflows
* Development teams
* Sprint planning

---

## 📊 Gantt

Visualize your project on a timeline.

Choose between:

* Weekly scale
* Monthly scale

Perfect for:

* Project deadlines
* Roadmaps
* Long-term planning
* Timeline visualization

---

# 🎨 Project Phases

SuperProject includes predefined phases with visual colors:

| Phase         | Color        |
| ------------- | ------------ |
| 🔵 Initiation | Blue         |
| 🟡 Planning   | Yellow       |
| 🟣 Execution  | Purple       |
| 🟠 Review     | Burnt Yellow |
| 🟢 Closure    | Green        |

These phases help organize your project from the first idea to final delivery.

---

# 🔍 Task Details

Click **⋯** on any item to open its details.

Inside each item, you can manage additional information through different tabs.

## 📝 Details

Configure:

* Description
* Priority
* Phase
* Type
* Deadline

---

## 🎯 OKR Canvas

The **OKR Canvas** appears when an item is marked as overall project planning.

Use it to organize:

* Objectives
* Key Results
* Strategic planning

---

## 📌 Kanban

For regular items, subtasks can be organized visually according to their progress.

---

## 🗺️ Roadmap

Organize subtasks according to:

* Priority
* Progress
* Planning structure

---

# 📅 Dates

Project dates can be configured from the home screen.

Open:

```text
Edit Project
```

There you can configure:

* 📅 Start Date
* 📏 Timeline Scale

Inside the project, the **Show Dates** button next to the Gantt allows you to turn date visualization on or off.

---

# 🤖 Using AI with SuperProject

SuperProject becomes especially powerful when combined with AI.

You can ask an AI to generate a complete project structure.

### Example prompt

```text
Create a complete project plan for an e-commerce platform.

Format the response using this structure:

Page - Task 1 - Task 2 - Task 3

Create pages for:
- Planning
- Design
- Frontend
- Backend
- Database
- Testing
- Deployment
```

The AI might generate:

```text
Planning - Define requirements - Create project scope - Define milestones
Design - Create wireframes - Create UI design - Define design system
Frontend - Setup React - Create authentication - Create dashboard
Backend - Create API - Implement authentication - Configure services
Database - Design schema - Configure PostgreSQL - Create migrations
Testing - Write unit tests - Perform integration tests - Fix bugs
Deployment - Configure production - Deploy application - Monitor errors
```

Paste it into SuperProject.

Done. 💥

Your project workspace is ready.

---

# 🆓 100% Free

SuperProject is free.

No subscription.

No premium tier required to use the platform.

No forced payment to manage your projects.

The goal is to provide a fast and accessible project management experience without unnecessary complexity.

---

# 📄 Single-File Architecture

The entire application is contained in a single file:

```text
index.html
```

That means you can:

1. Download the file.
2. Open it in your browser.
3. Start using SuperProject.

Simple.

---

# 🚀 Getting Started

Clone or download the project:

```bash
git clone <repository-url>
```

Then open:

```text
index.html
```

No build process required.

No package installation required.

No backend required.

---

# 🌟 Philosophy

SuperProject was built around a simple principle:

> **Project management should not take longer than the project itself.**

Instead of spending hours configuring tools, creating boards and manually adding tasks, you should be able to:

```text
Think → Generate → Paste → Organize → Execute
```

SuperProject focuses on:

* ⚡ Speed
* 🧠 Simplicity
* 🤖 AI compatibility
* 📊 Multiple visualizations
* 🆓 Free access
* 📄 Portable single-file architecture

---

# 🗺️ Workflow

A typical workflow looks like this:

```text
💡 Project Idea
      ↓
🤖 Ask AI to Structure It
      ↓
📋 Copy Generated Text
      ↓
📥 Import into SuperProject
      ↓
💥 Complete Workspace Created
      ↓
📊 Visualize in List / Frames / Kanban / Sprint / Gantt
      ↓
🚀 Execute the Project
```

---

# 💡 Example

Suppose you want to build a mobile app.

You could ask an AI to generate:

```text
Planning - Define MVP - Research competitors - Define target audience
Design - Create wireframes - Design UI - Create design system
Frontend - Setup project - Create authentication - Build dashboard
Backend - Create API - Setup database - Implement authentication
Testing - Test features - Fix bugs - Perform final QA
Launch - Deploy app - Publish documentation - Monitor feedback
```

Paste everything into SuperProject.

In seconds, you have:

* Multiple project pages
* Organized tasks
* A project structure
* A Kanban workflow
* A Sprint overview
* A Gantt timeline

Without manually creating every task.

---

# 🛠️ Technology

SuperProject is designed as a lightweight application contained in:

```text
index.html
```

The platform can run directly in the browser without requiring a traditional installation process.

---

# 🤝 Contributing

Ideas, improvements and contributions are welcome.

Possible contributions include:

* New views
* New import formats
* Better AI prompts
* UX improvements
* Export options
* Accessibility improvements
* Bug fixes
* New project templates

---

# ⭐ Support the Project

If SuperProject helps you organize your work:

* ⭐ Star the repository
* 🐛 Report bugs
* 💡 Suggest new features
* 🤝 Contribute improvements
* 📢 Share the project

---

# 🚀 Final Thought

You don't need to spend an hour creating your project structure.

Ask an AI to generate it.

Paste it.

And let SuperProject do the rest.

**From raw text to a complete project workspace in seconds.** 💥

---

## Made for speed.

## Built for simplicity.

## Powered by your ideas.

# 🚀 SuperProject

**Think. Paste. Organize. Execute.**
