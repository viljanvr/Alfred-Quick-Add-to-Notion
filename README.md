# Alfred-Quick-Add-to-Notion

This Alfred Workflow lets you quickly add tasks from Alfred to a Notion database using the Notion API. It will automatically parse dates written on different formats. 

To get the automation to work you need to retrive an `Internal Integration Token` and the `Database-ID` from Notion. Some changes in the Workflow may be required to suit your Notion setup (see [Notion API documentation](https://developers.notion.com/reference/property-value-object)).

The Workflow can be downloaded [here](/Quick%20Add%20to%20Notion.alfredworkflow).

## How to use the workflow

1. Press `cmd ⌘` + `space` to open Alfred and type *task {title} {date}*: ![Add new task](/Resources/Add%20task.png)


2. Select category from the dropdown list: ![Select category](/Resources/Select%20category.png)

3. The new task will appear like this in Notion: ![Notion database](/Resources/Notion.png)