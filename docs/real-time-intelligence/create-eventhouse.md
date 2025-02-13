---
title: Create an event house
description: Learn about how to create an event house for data storage in Real-Time Intelligence.
ms.reviewer: sharmaanshul
ms.author: yaschust
author: YaelSchuster
ms.topic: how-to
ms.date: 06/04/2024
ms.search.form: Eventhouse
#customer intent: As a user, I want to learn how to create an event house for data storage in Real-Time Analytics so that I can effectively manage my data.
---
# Create an event house

An event house allows you to manage multiple databases at once, sharing capacity and resources to optimize performance and cost. It provides unified monitoring and management across all databases and per database. For more information, see [Event house overview](eventhouse.md).

In this article, you learn how to create an event house, add new databases to an event house, rename, and delete an event house.

## Prerequisites

* A [workspace](../get-started/create-workspaces.md) with a Microsoft Fabric-enabled [capacity](../enterprise/licenses.md#capacity)

## Create an event house

1. Browse to your workspace homepage in Real-Time Intelligence.
1. Select **New** > **Eventhouse**.

    :::image type="content" source="media/eventhouse/new-eventhouse.png" alt-text="Screenshot of creating a new event house item in Real-Time Intelligence." lightbox="media/eventhouse/new-eventhouse.png"::::::

1. Enter a name for the event house. Both an event house and its default child KQL database are created with the same name. The database name, like all items in Fabric, can be renamed at any time.

    > [!NOTE]
    > The event house name can contain alphanumeric characters, underscores, periods, and hyphens. Special characters aren't supported.

1. The [system overview](manage-monitor-eventhouse.md#view-system-overview-details-for-an-event-house) opens in the main view area of the newly created event house.

    :::image type="content" source="media/eventhouse/choose-eventhouse.png" alt-text="Screenshot of system overview in the main view area." lightbox="media/eventhouse/choose-eventhouse.png":::

## Add a new database to an event house

1. From the explorer, select the **New database** [**+**].

    :::image type="content" source="media/eventhouse/add-database.png" alt-text="Screenshot showing the selector to add a new database.":::

1. Enter a database name, and select **Create**.

    :::image type="content" source="media/eventhouse/name-new-database.png" alt-text="Screenshot showing the pop-up box to name your new database.":::

1. The [Database details](create-database.md#database-details) page for your new database opens in the main view area.

    :::image type="content" source="media/eventhouse/database-details.png" alt-text="Screenshot of the database details page for your new database.":::

To learn more about creating KQL databases, see [Create a KQL database](create-database.md).

## Rename an event house

1. Browse to the event house item in your workspace.
1. Click on the name of the event house in the top left corner.
1. Enter a new name for the event house.

    :::image type="content" source="media/eventhouse/rename.png" alt-text="Screenshot of renaming an event house.":::

## Delete an event house

When you delete an event house, both the event house and all its child KQL databases are deleted forever.

1. Browse to the event house item in your workspace.
1. Select **More menu** [**...**] > **Delete**.

    :::image type="content" source="media/eventhouse/delete-eventhouse.png" alt-text="Screenshot of deleting an event house.":::

## Related content

* [Eventhouse overview](eventhouse.md)
* [Manage and monitor an event house](manage-monitor-eventhouse.md)
* [Create a KQL database](create-database.md)
