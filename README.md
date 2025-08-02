# Git & GitHub Version Control Simulation Project

This project simulates a real-world Git workflow using Git and GitHub. It includes branching, merging, tagging, conflict resolution, stash usage, and more — all within a simple HTML/CSS/JS web project.

What Was Built
A basic static website with:
- 'index.html': Contains a navigation bar and heading.
- 'style.css': Provides simple styling.
- 'script.js': Contains a placeholder JavaScript function.

The purpose of the project is not web development — but to practice Git commands in a real scenario.
Git Features Demonstrated

 Feature               Description                                     
 
 'git init'            Initialize a Git repo                           
 'git add' / 'commit'  Stage and save changes                          
 'git branch'          Create and switch between branches              
 'git merge'           Merge branches together                         
 'git stash'           Temporarily save uncommitted changes            
 'git log'             View commit history                             
 'git tag'             Mark version releases like 'v1.0', 'v2.0'       
 'git push/pull'       Sync with remote GitHub repo                    
 'git remote'          Connect to GitHub repository                    

Branching and Merging
- Created branches like  'feature/navbar', 'feature/footer'
- Edited 'index.html' to simulate new features
- Merged them into 'main' using 'git merge'
- Resolved conflicts when changes collided

Merge Conflict Simulation
1. Edited the same line in two branches
2. Tried to merge → Git showed a conflict
3. Manually resolved it and committed the fix

Git Tags
Created a version tag using:
  git tag v1.0
  git push origin v1.0
