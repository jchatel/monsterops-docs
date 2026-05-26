# Using the KPIs tab

The KPIs tab displays the statistics a team tracks to measure its performance. Use it to monitor numbers over time, see how individual owners are tracking against their targets, and anticipate where a metric is heading.

## How it works

KPIs can be viewed across **weekly, monthly, quarterly, and yearly** intervals, and filtered by owner to focus on a specific person's metrics. Each KPI also carries a forecast value to help you anticipate where the metric is heading for the current interval.

## How a KPI appears in the list

Each KPI row follows a consistent layout. Reading left to right, you'll see:

1. **Status** — a small icon showing the metric's recent graph and how it's performing against its target (see below for the icon variations).
2. **KPI title** — the name of the KPI.
3. **Owner** — the user accountable for the KPI.
4. **Forecast** — the expected value for the current interval.
5. **KPI metrics** — one column per interval based on your selected view (weekly, monthly, quarterly, or yearly). The **first column is always the most recent past interval**, with earlier intervals continuing to the right.
6. **Edit KPI** — direct button to open the KPI for editing.
7. **Delete KPI** — direct button to delete the KPI.

KPIs are the one item type that does not use the Additional settings dropdown (⁝). Instead, the Edit and Delete actions are surfaced directly on the row.

### Status icon variations

The status icon sits inside a circle and shows a small graph of the metric's recent values. The icon changes based on how the KPI is performing against its target:

- **No target** — a **dash** (gray)
- **Target met** — a **check mark** (gray, unless the design states otherwise)
- **Target at risk** — a **yellow triangle with an exclamation point**
- **Opposite of target** — a **red X**

Use the icon as a quick read on which KPIs are on track and which need attention before drilling into the numbers.

## What's included in a KPI

Each KPI includes required information used for measurement and tracking, plus optional fields for organization and context.

### Required fields

Every KPI must include:

- Icon
- Title
- Team
- Owner
- Supported Views
- Interpolation
- Target Type

The Owner is responsible for maintaining the KPI and its data.

### Optional fields

You can also add:

- Description
- KPI group
- Formula
- Reference Value
- Rock
- Links to related items

## Understanding KPI fields

Some KPI fields have specific behavior worth understanding before you set one up.

### Supported Views

Supported Views determine which time intervals — weekly, monthly, quarterly, or yearly — a KPI can be viewed across.

### Interpolation

Interpolation controls how values are calculated and shown across intervals. The options are:

- **No Interpolation** — values are shown only where they're recorded
- **Latest Value** — the most recent recorded value is used
- **Cumulative Value** — values accumulate over the selected interval
- **Average** — the average of values is shown over the selected interval

### Target Type

Target Type defines the kind of value the KPI is measuring. The options are:

- **Number**
- **Currency** — with an option to choose the currency type
- **Percentage**
- **Boolean**
- **Direction**
- **Time**

### Formula

Formula sets the comparison used when evaluating whether the KPI is meeting its target. It's available when the Target Type is **Number**, **Currency**, or **Percentage**. The options are:

- Less than or equal
- Greater than or equal
- Less than
- Greater than
- In between
- Equals

### Reference Value

Reference Value is the value the KPI is aiming for. Its format depends on the Target Type:

- **Number** — a numeric value
- **Currency** — a 2-decimal value
- **Percentage** — a value from 0 to 100
- **Boolean** — Yes or No
- **Direction** — up or down
- **Time** — a time value

### Forecast value

The forecast value is the expected value for the current interval, helping you anticipate how the KPI will end up before the interval closes.

### KPI group

KPI group lets you display related KPIs together for organization purposes, making it easier to review a set of connected metrics as a group rather than individually.

### Rock

Linking a KPI to a Rock ties ongoing measurement to the priority it supports, so the metric and the work behind it stay connected.

## Create and manage KPIs

1. Open a team.
2. Select the **KPIs** tab.
3. Create or open a KPI.
4. Add the required fields, including Supported Views, Interpolation, and Target Type.
5. Set the Formula and Reference Value if the Target Type supports them.
6. Optionally add a description, group, linked Rock, or related items.
7. Save the KPI.

## Adding Notes to a KPI

Notes let you attach additional context, follow-ups, or commentary directly to a KPI without changing its configuration. Use them to capture explanations for unusual values, context behind a target change, or follow-ups discussed in a meeting.

A Note lives on the KPI it's added to, so anyone opening the KPI sees its details along with any Notes that have been added to it.

### When to use a Note

- To explain a spike or dip in the metric
- To capture context behind a target or formula change
- To record follow-ups or decisions made in a KPI review
- To preserve a running history of how the metric has evolved

### Add a Note to a KPI

1. Locate the KPI you want to add a Note to.
2. Click the **note icon** to the far right of the KPI, just to the left of the three-button menu (Edit, History, Archive, Delete). When Notes already exist on the KPI, a number appears above the icon showing how many. Clicking it opens a compact view of the KPI, a thread of any existing Notes, and a text box for adding a new Note.
3. Type your Note in the text box.
4. Click **Add note** to post it.

Your Note appears in the thread alongside any earlier Notes, so the full history of context and updates stays with the KPI. Notes are deleted along with the KPI if the KPI is deleted — note that KPIs can't be archived, only deleted.

## Best practices

- Choose the interval that matches the metric's natural rhythm — review fast-moving KPIs weekly and slower ones quarterly or yearly.
- Pick the Interpolation that reflects how the data should be read across intervals; the wrong choice can make a healthy metric look unhealthy.
- Use the owner filter to give each person a clear view of the metrics they're accountable for.
- Connect a KPI to a Rock when the metric measures the success of that priority.
- Group related KPIs so the team can review connected metrics together rather than one at a time.
- Use Notes to explain unusual values or capture context, so future viewers understand what the numbers mean.

## Things to keep in mind

- KPIs can be deleted but not archived — unlike News, Rocks, To-dos, and Issues.
- Deleting a KPI is permanent, and any Notes on it are deleted with it.
- A KPI belongs to one team. It can be moved to another team or owner, but it can't be co-owned.
- Formula is only available for Number, Currency, and Percentage Target Types.
- Reference Value formatting follows the Target Type — for example, Percentage values run from 0 to 100, and Currency uses 2 decimals.
- Forecast value reflects the expected value for the current interval based on data so far.

## Related articles

- Using Notes
- Linking items together
- Icons, Tags, and shared item elements
- Keyboard shortcuts
- Create and manage Rocks
- Using the Team Dashboard
- Using the Issues tab
- Running meetings
