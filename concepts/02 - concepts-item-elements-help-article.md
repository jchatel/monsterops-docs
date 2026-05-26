# Icons, Tags, and shared item elements

A few elements appear consistently across the items you can create in MonsterOps — News, Rocks, To-dos, Issues, and KPIs all share the same patterns for icons, tags, and the controls on the right side of each item. This article covers those shared elements so you don't have to relearn them tab by tab.

## Icons

Every item has an Icon displayed on its left side. Icons make items easier to scan at a glance and let you visually distinguish related work.

### Default and custom icons

New items start with a default black Rock icon. You can change the icon when creating or editing the item:

1. Click the icon on the item.
2. Choose a color from the available palette, or pick a custom color.
3. Choose a stock icon from the gallery, or use the search field to find a specific one.

The icon updates immediately and is reflected wherever the item appears.

## Tags

Tags are optional labels you can add to items. When applied, they appear directly under an item's title.

Tags are purely visual — they're a way for the team to quickly see what category or theme an item falls under at a glance. They don't drive any filtering or grouping behavior, so think of them as labels for human readers rather than a way to organize the system.

## The right-side controls on an item

Each item carries a consistent set of controls on its right side:

- **Note icon** — opens the item's Notes thread. A number appears above the icon when Notes already exist on the item, showing how many. See **Using Notes** for details.
- **Additional settings dropdown (⁝)** — on the far right of the row, containing **Edit**, **History**, **Archive**, and **Delete**.

KPIs are an exception: they don't use the Additional settings dropdown. Instead, the Edit and Delete actions appear as direct buttons on the row, and KPIs don't support Archive at all.

### Edit

Opens the item to change its fields.

### History

Opens a popup showing the detailed change history for the item. Each entry includes:

- **Who** made the change
- **What** changed, including the original value of the changed field
- **Whether the change was made during a meeting**, so you can trace updates back to the session where they happened

History is useful when you need to understand how an item got to its current state — for example, when a Rock's status was updated, or who changed a KPI's target.

### Archive

Moves the item to its Archived view. Archiving is reversible, and the trigger varies by item type:

- **News, To-dos, Issues** — tick the item off as done/solved on its left side
- **Rocks** — mark the Rock as Completed

Note that **KPIs cannot be archived**, only deleted.

### Delete

Removes the item permanently. Deletion cannot be undone, and any Notes on the item are deleted with it.

## Owner vs. Assignee labeling

Most items in MonsterOps use the field name **Owner** (News, Rocks, KPIs). To-dos and Issues use **Assignee** internally — when you create or edit one of these items, you'll see "Assignee" in the form. However, both items display **"Owner"** as the column label in the list view.

The two terms refer to the same concept: the user accountable for the item. The label mismatch between the create/edit view and the list view is a quirk of how each item type is built.

## Visual indicators

A few visual indicators appear consistently across item types so you can spot important context at a glance:

### Past-due dates

Any due date that's already passed is displayed in **red text**. This applies wherever a due date appears — in item rows, inside meetings, and in detail views — so overdue work is easy to catch even when you're scanning quickly.

### NEW indicator

Items created less than **24 hours ago** display a **NEW** indicator next to their title. The indicator disappears automatically once the item is more than 24 hours old, so it surfaces recent activity without lingering.

This is useful for spotting items that were just added — for example, an Issue raised in this morning's meeting or a To-do created by a teammate yesterday afternoon.

## Permissions for shared item actions

The shared item actions — Edit, History, Archive, and Delete — are open to anyone in the team. This includes deleting items that were created by users with higher permission levels (for example, a Member can delete a Rock created by an Owner). Because deletion is permanent and any Notes go with it, exercise care when removing items you didn't create.

## Things to keep in mind

- Anyone in a team can edit, archive, or delete items, regardless of who created them. Deletion is permanent.
- Icons and tags are visual aids — they don't affect how an item behaves, only how easy it is to find.
- Archiving is reversible across all item types that support it; deletion is permanent.
- Items belong to one team at a time. They can be moved between teams or owners, but they can't be co-owned.
- **KPIs are an exception** in two ways: they can be deleted but not archived, and they use direct Edit / Delete buttons instead of the Additional settings dropdown used by other items.
- **To-dos and Issues label "Assignee" as "Owner"** in the list view, even though the internal field name is Assignee. Both refer to the same accountable user.

## Related articles

- Using Notes
- Linking items together
- Using the News tab
- Using the Rocks tab
- Using the To-dos tab
- Using the Issues tab
- Using the KPIs tab
