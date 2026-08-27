# Concepts in MonsterOps

MonsterOps uses a small set of recurring concepts across the product. This article defines each one in a single place so you can use it as a quick reference. For full details, follow the link in each entry.

## Organization

The Organization is the top-level entity in MonsterOps. It contains teams, members, Objectives, the Org Chart, and Core Values, plus admin areas for Billing / Plan, Team Members, and Settings. Most things in MonsterOps belong to a team within the Organization. A single user can belong to multiple Organizations and switch between them from the Organization selector at the top of the left-side navigation.

See **Working with your Organization** for details, or **Creating a new Organization** for how to set up an additional one.

## Permission levels

MonsterOps has three permission levels:

- **Owner** — highest standard level
- **Admin** — can do most Organization-level actions
- **Member** — the default level for users

Permission gating applies in several places: Organization Settings (Owner/Admin only), changing user permission levels (Owner/Admin only, with Admins unable to self-demote), Objectives direct edits, Org Chart role edits, approving email domains, and removing team members. Members trying these actions see a red "Only organization owners or admins can perform this action" popup. Most other everyday actions — creating items, inviting team members, running meetings — are open to all members.

A separate **Super Admin** level exists for internal access. Team deletion through the Danger zone is restricted to the Organization Owner and Super Admins; regular Admins cannot delete teams.

## Team

A team is a group of users working together inside an Organization. Each team has its own tabs (News, Rocks, KPIs, To-dos, Issues, Meetings) plus a Team Dashboard, Team Members, and Team Settings.

See **Working with Teams** for details.

## Objective

An Objective is a company-level goal. Objectives sit at the top of the goal hierarchy in MonsterOps and work best on a 6-month to 1-year horizon. Rocks can be linked to Objectives, and the Objective's progress reflects the status of all linked Rocks.

See **Setting and tracking company goals with Objectives** for details.

## Rock

A Rock is a major priority a team is driving, typically across one quarter. Rocks have a status (On-track, At-risk, Off-track, Completed, Cancelled, Planned and Backlog) and can include milestones — smaller stages of work with their own statuses, owners, and due dates. Rocks can be linked to Objectives so their progress rolls up to company-level goals.

See **Using the Rocks tab** for details.

## Milestone

A milestone is a stage of work inside a Rock. Each milestone has a status, name, due date, and owner. Milestone statuses use the same options as Rocks, and completing milestones automatically advances the Rock's overall progress.

## KPI

A KPI is a statistic the team tracks to measure performance. KPIs can be viewed across weekly, monthly, quarterly, and yearly intervals, and each carries a forecast value for the current interval. KPIs have specific configuration fields like Interpolation, Target Type, Formula, and Reference Value.

See **Using the KPIs tab** for details.

## To-do

A To-do is a short-term action item or near-term piece of work. To-dos are designed for day-to-day operational work and follow-ups. They appear on the Team Dashboard so they can be ticked off without opening the To-dos tab.

See **Using the To-dos tab** for details.

## Issue

An Issue is an obstacle, risk, or unresolved question the team needs to work through. Issues are organized by Timeframe (Short term, Long term) and Priority (a 0–5 scale). Issues don't have a target date — if one becomes time-sensitive, it can be converted into a To-do.

See **Using the Issues tab** for details.

## News

News is a team-level update or announcement. News items are visible to the team and live in either the Active or Archived section of the News tab.

See **Using the News tab** for details.

## Meeting

A meeting is a structured team session built around an Agenda. Meetings include attendance, a section timer, real-time updates to KPIs and To-dos, and a Conclusion step with attendee scores and notes.

See **Using the Meetings tab** for details.

## Agenda

An Agenda is the template that defines what a meeting will contain. Each team includes a default Weekly Team Meeting agenda, and you can create custom agendas with different step types (Icebreaker, KPI, News, Issue, Rock, OS Toolbox, To-do, Conclude, Custom).

See **Building and managing Agendas** for details.

## Owner / Assignee

Owners and Assignees are functionally the same concept — both identify the user accountable for an item. The field is called **Owner** on News, Rocks, and KPIs. On To-dos and Issues, the field is internally called **Assignee** but displays as **Owner** in the list view. Either way, the person named is responsible for maintaining and driving the item forward.

## Items

"Items" is a general term covering anything you can create that belongs to a team: News, Rocks, To-dos, Issues, KPIs. They share several common elements — icons, tags, the Additional settings dropdown (Edit, History, Archive, Delete), and the Notes feature. KPIs are an exception in that they use direct Edit and Delete buttons instead of the dropdown.

See **Icons, Tags, and shared item elements** for details.

## Notes

Notes are short messages you can attach to an item to add context, progress updates, or follow-ups. Notes appear in a thread on the item itself and are visible to anyone who can see the item.

See **Using Notes** for details.

## Linked items

Linked items are connections between items. Linking a To-do to a Rock, or a Rock to an Objective, helps connect related work across the team. Linking is done from the item's edit view.

See **Linking items together** for details.

## Keyboard shortcuts

MonsterOps supports a small set of single-key shortcuts for creating items quickly from anywhere in the product: **N** (News), **R** (Rock), **K** (KPI), **T** (To-do), **I** (Issue).

See **Keyboard shortcuts** for details.

## Core Values

Core Values are the beliefs that guide how the team makes decisions and shows up day to day. They're defined at the Organization level and are visible to everyone in the Organization.

See **Adding and managing Core Values** for details.

## Org Chart

The Org Chart visualizes the Organization's structure around roles and accountability rather than titles. Each role has responsibilities and a reporting relationship; users can hold multiple roles, and multiple users can share a role.

See **Understanding the Org Chart** for details.

## MonsterAI

MonsterAI is the built-in assistant that helps you understand, navigate, and find information in MonsterOps. It can explain features, summarize team activity, and answer questions using both help content and team data.

See **Getting help with MonsterAI** for details.

## Interface navigation

MonsterOps's interface is divided into a **left sidebar** (Organization selector, Get Started, Organization sections, Views, Teams, and user controls) and a **top bar** (sidebar toggle, breadcrumbs, MonsterAI agent, Create item button, language switcher, dark mode toggle).

See **Navigating the MonsterOps interface** for details.

## User account

Each user has their own account, accessed from the profile section at the bottom of the left sidebar. It includes user settings (Profile settings with email reminders and DISC Profile, plus Security settings for passkey and password), the language switcher, and the sign-out control.

See **Managing your user account** for details.

## User profile

A public-facing page for each user in the Organization, accessed from Team Members. It shows the user's name, level, DISC style, contribution graph, and recent activities. Distinct from the User account, which is the user's own private settings.

See **Viewing a teammate's profile** for details.
