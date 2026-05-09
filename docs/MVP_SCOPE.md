# One Piece Watch Companion — MVP Scope

## MVP goal
Build the first simple working version of the website.

The MVP should help one friend:
- see their One Piece watching progress
- view personal episode or arc references
- receive thank-you or reward messages
- send a reaction by email or simple form

## In scope

### 1. Home page
The home page should include:
- personal welcome message
- short explanation of the website
- current progress preview
- links to progress, references, and reactions

### 2. Progress tracker
The progress tracker should show:
- current episode
- current arc
- watched status
- simple progress information

For the first version, progress can be updated manually in a local data file.

### 3. Episode / arc references
The website should show reference cards with:
- episode or arc name
- short personal message
- spoiler-safe note if needed

### 4. Thank-you messages
The website should include small reward messages after:
- important episodes
- finished arcs
- progress milestones

### 5. Reaction / email flow
The first version can use a simple `mailto:` email button.

A complex backend form is not required for MVP.

## Out of scope
The MVP will not include:
- user accounts
- login system
- complex admin panel
- public comments
- payments
- notifications
- multiple users
- complex database

## Planned pages

```text
/
 /progress
 /references
 /reactions
