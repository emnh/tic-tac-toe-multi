# tic-tac-toe-multi
Tic Tac Toe Multiplayer
 - What is the criteria for choosing technologies?
  - Amount of work
  - Benefit
  - Decision fatigue
- Alternatives
  - JS/HTML with esbuild or webpack
  - Blazor on Linux
  - Blazor in Azure Free App Service Plan (downside it's 60 CPU minutes per day, won't scale)
  - Blazor in Azure Paid Service Plan (10$/month shared, 50$/month S1 dedicated)
  - Do I want static typing?
  - Do I want to use an IDE like VS Code or Visual Studio?

# Okay

Decisions made:
 - Blazor App
 - Data stored in SQL server on emh.lart.no
 - SQL Settings: Separate database and separate user.
 - How to configure SQL? Idempotent master script for setup?
