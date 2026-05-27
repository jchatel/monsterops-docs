# Working with your Organization

The Organization is the top-level entity in MonsterOps. It contains your teams, members, and the company-level features that sit above any single team. This article gives you the map.

## How the Organization is structured

The Organization is split into three main areas you'll find in the left-side navigation:

- **Objectives** — company-level goals that Rocks are linked to
- **Org Chart** — the function-based structure of roles and responsibilities
- **Core Values** — the beliefs that guide how the team makes decisions

In addition, every Organization has its own three-dot menu (located on the Organization itself in the left-side navigation), which opens three admin areas:

- **Billing / Plan** — payment method and current subscription
- **Team Members** — the people who belong to your Organization, with their permission levels and team memberships
- **Settings** — Organization-wide configuration, branding, terminology, and API integrations

## Organization-level features vs. team-level features

It's worth understanding what sits at the Organization level versus inside a team:

- **Organization level**: Objectives, Org Chart, Core Values, Billing/Plan, Organization-wide Team Members, Settings
- **Team level**: News, Rocks, KPIs, To-dos, Issues, Meetings, Team Dashboard, Team Members (per-team), Team Settings

Some terms overlap — "Team Members" exists at both levels, but with different scope. Organization Team Members covers everyone in the Organization and their permission levels; the team-level Team Members section only covers who's on a particular team.

## Permission levels

The Organization has three permission levels:

- **Owner**
- **Admin**
- **Member**

Permission gating applies in several places:

- **Organization Settings** is restricted to Owners and Admins.
- **Changing other users' permission levels** is restricted to Owners and Admins (an Admin can't demote themselves — only an Owner can demote an Admin).
- **Objectives** (direct create/edit/archive/delete) is restricted to Owners and Admins, though Members can influence Objective progress indirectly by linking their Rocks.
- **Org Chart roles** (add, edit, delete) is restricted to Owners and Admins.
- **Approving email domains** and **removing team members** is restricted to Owners and Admins.

Most other everyday actions — creating items, joining and managing teams, inviting team members, creating new teams, running meetings — are open to anyone.

A separate **Super Admin** level exists for internal access. Team deletion is restricted to the Organization **Owner** and Super Admins; regular Admins cannot delete teams through the product.

See the individual articles below for more on how each Organization-level feature works.

## Related articles

- Creating a new Organization
- The Organization Dashboard
- Working with Teams
- Setting and tracking company goals with Objectives
- Understanding the Org Chart
- Adding and managing Core Values
- Organization Billing and Plan
- Organization Team Members
- Organization Settings
