# brickster 0.2.4

* `open_workspace()` and the rstudio connection pane have been heavily revised
  to enhance browsing unity catalog and also remove DBFS and WSFS browsing (#52)

# brickster 0.2.3

* Adding NEWS.md
* Renamed `set_lib_path` to `add_lib_path` and added the `after` parameter
* Adding OAuth U2M support (workspace level), considered the default when
  `DATABRICKS_TOKEN` isn't specified (e.g `db_token()` returns `NULL`)
* Updating authentication vignette to include information on OAuth
* Updating README.md to include quick start and clearer information
* Adding vector search index functions