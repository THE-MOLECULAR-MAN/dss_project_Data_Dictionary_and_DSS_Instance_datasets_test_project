# Prerequisite:
You'll need to have a [PostgreSQL connection working in DSS](https://doc.dataiku.com/dss/12/connecting/sql/postgresql.html) before you can use this project. Only DSS adminisrators can add connections.

# Importing the plugin
1) [Visit the Datasets about Dataiku Plugin release page](https://github.com/THE-MOLECULAR-MAN/dss-plugin-xzibit/releases)
2) Find the latest release for DSS version 12 (not version 14). Click on Source code (zip) to download the file.
3) It should download a file named something similar to dss-plugin-xzibit-DSSv12_plugin_v1.0.0.zip
4) In DSS v12, select the Administration menu, then Plugins
5) Add Plugin > Upload
6) Attach the ZIP file you downloaded in step 3.
7) On the next page, click Build New Environment.

Once that finishes, the plugin should be ready to use.

# Importing the project
1) Download the DSS Project sent from your Sales Engineer. For example: DSS_v12_Upgrade_Planning_Toolkit-v1.0.0.zip . Note that this is a different file from the plugin.
2) On the homepage of DSS v12, click the blue New Project button, then Import Project.
3) Click Choose File and select the project zip file from step one.
4) Check the Display advanced options after upload checkbox
5) Click the blue Import button
6) Under connection remapping, click Add remapping.
7) Click in the empty textbox and select postgres_local.
8) In the dropdown menu on the right, select the PostgreSQL connection you want to use.
9) Click the blue Import button
10) You may see a warning about other plugins that were installed - you can ignore this.

# Using the project
Open the project and visit its Wiki page for instructions on how to build the dashboards.
