# Macro Parameters

* Macro parameters are populated from a database table, these correspond to controls (which implement `IMacroGuiRendering`). Could we reuse existing data-type (configured definitions, not the raw control) as macro parameters? Hook into save event to populate the database table with a proxy control and data-type-definition Id, (so to render the underlying control)?

> I attempted to prototype this functionality, (within uComponents), but hit a brick-wall!
> If you think you've got a better approach, please [open an issue](https://github.com/leekelleher/umbraco-package-ideas/issues) for discussion.
