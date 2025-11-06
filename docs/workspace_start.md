# **Getting Started in Workspaces**

MC2DP workspaces are secure data analysis environments in the cloud that can access data from one or more data resources. By default, Workspaces include Jupyter notebooks at this time.

>New to Jupyter? Learn more about the popular tool for data scientists on [Jupyter.org](https://jupyter.org/) (disclaimer: CTDS is not responsible for the content).

## Guidline to get started in Workspaces
Once users have access to workspaces, use this guide below to get started with analysis work in workspaces.

1. Users need to log in via https://mc2dp.data-commons.org/login to access workspaces.

2. After navigating to https://mc2dp.data-commons.org/workspace, users will discover a list of pre-configured virtual machine (VM) images, as shown below.

[![Workspace Launch Tiles][img-workspace_launch_tiles]](https://mc2dp.data-commons.org/workspaces)

3. Click “Launch” on any of the workspace options to spin up a copy of that VM. The status of launching the workspace is displayed after clicking on “Launch”. Note: Launching the VM may take several minutes.

[![Workspace Request Status][img-workspace_request_status]](https://mc2dp.data-commons.org/workspaces)

4. After launching, the home folders are displayed. One of these folders is the user's persistent drive (`/pd`).

[![Workspace Directory Structure][img-workspace_directory]](https://mc2dp.data-commons.org/workspaces)

5. Select the `/pd` folder. New files or licenses should be saved in the the `/pd` directory if users need to access them after restarting the workspaces. Only files saved in the `/pd` directory will remain available after termination of a workspace session.
    - Use this folder to store files (notebooks, data files, etc) that you want to use again later. The files you save here will still be available when you come back after terminating your workspace session.
    - Any files you create or add outside of this folder will be lost if they are not moved to the /pd before your workspace session terminates.

6. Start a new notebook under “Notebook” in the Launcher tab. Click the tiles in the launcher and choose between Python 3 or R Studio as the base programmatic language.

[![Workspace Launcher][img-workspace_launcher]](https://mc2dp.data-commons.org/workspaces)

7. *Experiment away!* Code blocks are entered in cells, which can be executed individually or all at once. Code documentation and comments can also be entered in cells, and the cell type can be set to support Markdown.

8. Do not forget to close your workspace once your work is finished. Unclosed workspaces continue to accrue computational costs. Note, Workspaces automatically shut down after several minutes of idle time.

[![Workspace Close][img-workspace_close]](https://mc2dp.data-commons.org/workspaces)

<!-- Links and Images -->
[mc2dp-Platform-Profile]: https://mc2dp.data-commons.org/Profile
[img-workspace_launch_tiles]:  ./img/workspace_launch_tiles.png
[img-workspace_request_status]:  ./img/workspace_request_status.png
[img-workspace_directory]:  ./img/workspace_directory.png
[img-workspace_launcher]:  ./img/workspace_launcher.png
[img-workspace_close]:  ./img/workspace_close.png