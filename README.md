Project Info:

Engine: Godot 4.x

Language: GDScript

Project Type: 3D Game

Main Scene: scenes/Main.tscn

How to Run the Project:

Install Godot 4.x from the official website

Open Godot → Click Import

Select the project folder (this repository)

Open the project

Press F5 or click ▶️ Run Project

controls:

move forward, left, right, back, w, a, d, s respectively

jump, space bar

project_root/
│
├── scenes/        # All .tscn scene files
├── scripts/       # All GDScript files
├── assets/        # Sprites, audio, fonts, etc.
├── ui/            # UI scenes and scripts
├── project.godot  # Godot project file
└── README.md

General Rules:

Do NOT rewrite the entire project

Only modify files necessary for the requested feature

Do NOT rename or move files unless required

Keep changes minimal and focused

Preserve existing functionality

Do NOT delete assets unless explicitly instructed

Code & Style Guidelines:

Use GDScript (Godot 4 syntax)

Use tabs (default Godot formatting)

Follow existing naming conventions

Keep scripts small and readable

Add comments only when helpful

Gameplay Implementation Rules

When adding new features:

Use proper Godot nodes (CharacterBody3D, Area3D, etc.)

Connect signals correctly

Avoid hard-coded node paths when possible

Prefer exported variables for tunable values

Ensure the project runs without errors

Definition of Done

A task is complete ONLY if:

The project runs successfully (F5)

No errors appear in the output console

New features work in gameplay

Existing features remain functional

All added files follow the project structure

Testing Changes

After making changes:

Run the project

Test the affected feature

Check for errors or warnings

Ensure controls still work

Things NOT to Do

Do not upgrade the Godot version

Do not change project settings unnecessarily

Do not remove input mappings

Do not refactor unrelated systems

Do not add external dependencies
