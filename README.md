# *Guidelines for Research Assistants*

Contents:
1. Administrative tasks
    1. [Managing project tasks with Asana](#i-managing-project-tasks-with-asana). Setting up Asana, keeping track of work, defining meeting agendas.
        1. [Setting up new projects](#setting-up-new-projects)
        2. [Using sections, columns, tasks and subtasks to keep track of work](#using-sections-columns-tasks-and-subtasks-to-keep-track-of-work)
        3. [Tracking priorities in the admin section](#tracking-priorities-in-the-admin-section)
        4. [Following up on presentation comments](#following-up-on-presentation-comments)
    3. [Managing meetings](#ii-managing-meetings). Preparing agendas before meetings, sending meeting recaps and keeping a record of previous meetings.
    4. [remindR deadline tracker](#iii-keeping-track-of-conference-and-presentation-deadlines). Using [remindR](https://github.com/clandinq/remindr) to keep track of important conference and presentation deadlines.
2. Keeping files organized
    1. [Working with GitHub](#i-working-with-github). Setting up and using GitHub locally and in the server.
        1. [Setting up a new repo on GitHub and cloning locally](#setting-up-a-new-repo-on-github-and-cloning-locally)
        2. [Setting up an existing repo on the server or a new computer](#setting-up-an-existing-repo-on-the-server-or-a-new-computer)
        3. [Updating the GitHub repo](#updating-the-github-repo)
    2. [Working with KLC](#ii-working-with-the-kellogg-linux-cluster-klc-server). Setting up the server and keeping project updated with GitHub.
        1. [Accessing KLC](#accessing-klc)
        2. [Uploading files with FileZilla](#uploading-files-via-filezilla)
        3. [Running scripts](#running-scripts)
3. Coding best practices
    1. [Working with EPS figures](#i-working-with-eps-figures)

# 1. Administrative tasks
## i. Managing project tasks with Asana
We use [Asana](https://asana.com/) to keep track of project tasks, provide updates and follow up on meetings. Before setting up Asana, read the [product guide](https://asana.com/guide/help) and [common questions](https://asana.com/guide/help/faq/common-questions) to understand how Asana works. As a very brief introduction, Asana has five levels of organization:
1. **Organizations**. Your user will be part of the Northwestern Kellogg organization. This is defined by the email address you use, so it is important that you register with your @kellog.northwestern.edu email address.
2. **Teams**. Teams are comprised of groups/sections of tasks (what asana calls "projects") and team members. We will have one team per academic project.
3. **Projects**. Projects are groupings of tasks in similar categories.  For example, we will always have an Admin and Analysis section in our Projects, and these sections are what Asana defines as projects. In the rest of this guide, I will refer to academic projects as *Projects*, and the subcomponents/sections of Asana teams and workspaces as *projects*.
4. **Tasks**. Tasks are individual components of projects that contain deadlines, descriptions and opportunities to comment and upload content. Tasks can be assigned to multiple projects.
5. **Subtasks**. Tasks are subdivisions of tasks that function in the same way, allowing you to set deadlines and update content.

### Setting up new Projects
1. First, download and install [Asana](https://asana.com/). For Asana to function correctly, you must register with your Kellogg email, which will grant you access to the Kellogg organization on Asana. 
2. Create a new team by clicking on **Add Team** in the left panel. We will have one team per Project, and if you're working on more than one Project, you will be able to see all the teams in the same window.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_1.png" align="center" height="30%" width="30%">

2. Write down the name of the Project (preferrably one or two words) and a short description. You can start inviting members at this point, but you will have to add them to each Asana project once they are created.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_2.png" align="center" height="35%" width="35%">
    
3. The next step is to create Asana projects, which will be sections of our Project.
    1. Click on **Create a Project** below the selected team.

        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_3.png" align="center" height="30%" width="30%">
        
    2. Select **Blank project** for project setup.
    
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_4.png" align="center" height="40%" width="40%">
    
    3. Define the section's name (e.g. "Admin"), choose **Board** as the default view, and leave privacy settings as **Public to team**. Click **Continue** to finalize creating this project. If you forget to set this up when creating the project, you can configure Board as the default view in the project settings.
        
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_6.png" align="center" height="30%" width="30%">
        
    4. Click on **Start adding tasks** and **Go to project**.
        
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_7.png" align="center" height="30%" width="30%">
        
    5. By default, the project will have three columns: To do, In progress, and Complete. Add a fourth column called "Archive".
        
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_8.png" align="center" height="50%" width="50%">
        
    6. Once you have set up an initial project, click on the three dots next to the project name and select **Duplicate Project**. Duplicate the project to generate a section called Admin, a second one called Agenda, and a third one called Analysis. These three sections will be the base of the Project, since most tasks will fall into the Analysis category, Agenda is used for meetings, and Admin will contain administrative tasks. More details are explained in the [following part of the guide](https://github.com/clandinq/ra_guide/#using-sections-to-keep-track-of-different-types-of-tasks).

        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_9.png" align="center" height="40%" width="40%">
        
    7. For each duplicated project, click on the down arrow next to the project name, and change the project's color so that it is easily identifiable.
    
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_11.png" align="center" height="40%" width="40%">
        
    8. Here is an example of how the sections of a Project looks like:
        
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/asana_setup_12.png" align="center" height="25%" width="25%">        
        
    9. Once all projects have been set up, invite all researchers and RAs as collaborators to the team.Once they have accepted your invitation, you can (and should) invite them to join the rest of the projects.  Ask collaborators (by assigning them a first task) to input their full name and a picture so that it's easy to identify task ownership. You can invite new members to a maximum of three projects. You can see who is a member of each project on the left of the search bar: 
    
        <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/colab_1.png" align="center" height="40%" width="40%">        
        
### Using sections, columns, tasks and subtasks to keep track of work
#### Sections
Keep different types of tasks in separate sections. Most projects will have the following sections:
- **Admin**: This section should contain administrative tasks. For example, writing up presentation comments and organizing tasks in Asana.
- **Agenda**: Keep items to be discussed in meetings in this section. Also, there should be a category (column) titled "Priorities" with the priorities of all the team members. This is explained more in detail in the [next part of the guide](https://github.com/clandinq/ra_guide/#keeping-track-of-agenda-contents).
- **Analysis**: All analysis-related tasks will be in this section. This should be the center of any project.
- **Presentations**: Tasks for presentations and conferences.
- **References**: Relevant references to keep in mind when writing the paper.
- **Comments**: Presentation comments. More details in the following sections.

Other sections projects can have include:
- Budget
- Grant deliverables
- Surveys

Feel free to set up new sections if necessary.

#### Columns
Most sections should have the following columns:
- **To do**: Tasks that have not been started yet.
- **In progress**: Tasks you are currently working on.
- **Complete**: Recently completed tasks.
- **Archive**: Completed tasks that have been discussed with researchers and whose output has been acknowledged. 

When completing a task, move it to the **Complete** column and add the task to the **Agenda** section to ensure it gets discussed in the next meeting with PIs. If it's a minor task that does not to be discussed in a meeting, you can assign a subtask to a PI so that they review what you've done, or alternatively, tag them in a comment. Once the task has been acknowledged, and if there are no more follow-up tasks that will be assigned to the same item, you can mark it as complete by clicking the check mark button and moving it to **Archive**.

#### Tasks and subtasks
All the work you do can be added as tasks and subtasks. The following is an example of a couple of tasks in Asana:

<img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/task.png" align="center" height="25%" width="25%">

Lengthier tasks should be broken down into subtasks:

<img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/subtask.png" align="center" height="40%" width="40%">

General guidelines for working with tasks and subtasks:
- **Naming**: Tasks and subtasks should have clear, short names that makes it easy to identify them. You can write down a full breakdown of the required task in the description section of the task or subtask. 
- **Deadlines**: When creating tasks, assign them to the main person responsible for completing the task, and assign a deadline. They are generally not hard deadlines, but can help to prioritize and identify tasks that have dragged on for longer than necessary. For tasks assigned to you, if the person creating the task did not put a deadline, set your own deadline to give the researchers a sense of when you think the task will be completed by. Subtasks can also have deadlines assigned to them. 
- **Adding results**: When adding results (graphs or tables), attach them as screenshots or JPG / PNG files, since PDF and EPS files will not show previews. If necessary, you can also attach Excel documents. If the description does not include it, add the reason why the analysis is being conducted, what the hypothesis was being tested, whether the results confirm or reject the hypothesis, and what can be concluded from the results.
- **Likes**: Use the like button to indicate that you've seen a task that has been assigned to you.

### Tracking priorities in the admin section
The first column in the **Admin** section should be called "Priorities", and will include a task for each team member with their priorities:

<img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/priorities_1.png" align="center" height="25%" width="25%">     

Include as subtasks current tasks by order of priority, with the most important tasks first. Delete subtasks when completed. This is so that it's easier to keep track of current tasks (since most of the time there will be several tasks assigned to you), and that PIs can know what your curent priorities are. **Always keep this section up to date**. Here is an example of a priorities task:

<img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/priorities_2.png" align="center" height="40%" width="40%">     

### Keeping track of agenda contents
The agenda section is used to keep track of current priorities and items to be discussed in each meeting. Start by creating a column for each regular meeting:

<img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/agenda_0.png" align="center" height="50%" width="50%">     

Follow these steps to add tasks to the agenda:
1. Click on a task that you want to add to a meeting agenda.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/agenda_1.png" align="center" height="25%" width="25%"> 
    
2. Click on **Add to projects** and select **Agenda**.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/agenda_2.png" align="center" height="30%" width="30%"> 
  
3. Select the meeting to add the task to.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/agenda_3.png" align="center" height="30%" width="30%"> 

4. The other section's color will display in the selected task. For example, this task is in the section **Analysis** and the Admin's section pink color is drawn over the task.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/agenda_4.png" align="center" height="25%" width="25%"> 

5. Once you have added all relevant tasks to the agenda, it will be easier to write the agenda email and add the detailed agenda to the Google Docs with detailed agendas and meeting recaps.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/agenda_5.png" align="center" height="25%" width="25%"> 

### Following up on presentation comments
PIs receive valuable comments from conferences where they present their academic projects. Asana can help convert these comments to actionable tasks, and by grouping comments by topic, prioritize which should be worked on first.

1. After each paper presentation, add a task in **Admin** asking the presenter to share the comments from the presentation. If you have the opportunity of being at the presentation, write down _every_ question asked, and who asked the question.
2. Create a document in the Project's Dropbox where you keep all presentation comments (example [here](https://github.com/clandinq/ra_guide/blob/main/docs/Presentation%20comments.docx)). Color-code comments from PIs and RAs and highlight comments that should become tasks:

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/comments_1.png" align="center" height="40%" width="40%"> 

3. Add comments to the **Comments** section on Asana. Group comments by topic, and make sure to assign actionable comments to the **Analysis** section.

    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/comments_2.png" align="center" height="50%" width="45%"> 
    <br/><br/>
    <img src="https://github.com/clandinq/ra_guide/blob/main/pictures/asana/comments_3.png" align="center" height="40%" width="40%"> 
    
4. Once a comment has been dealt with (either task has been done, or PI has responded the comment), move the comment to the **Complete** column in the **Comments** section. Assign the task to PIs so they can review, and once processed, ensure they are marked as complete and moved to the **Archive** column.

## ii. Managing meetings
1.	Send a meeting agenda as early as possible before each meeting with detailed items to discuss in the meeting and attaching all content relevant to the meeting. A useful way to remember is to set a calendar event with an email reminder for the agenda an hour or more before the meeting. Keep track of content for each meeting in Asana:
    1. Keep track of agenda items by adding them as tasks in an Asana project titled ???Agenda???. 
    2. Make a different section for each recurring meeting, and update tasks with what was discussed in the presentation. 
    3. When tasks are complete, mark as complete and move to a section titled ???Archive???.
2.	Send a meeting recap after each meeting with detailed notes about what was discussed in each meeting.
    1. Each item should have a discussion and tasks section.
        1. In the discussion section, write comments when possible as problem + potential solution.
        2. Immediately add items from tasks section to Asana.
    2. Upload summaries to a Google Docs document, and include this link in all recap emails.

## iii. Keeping track of conference and presentation deadlines
One important aspect of RA work is keeping track of deadlines related to presentations and grants. Professors must keep track of several deadlines: 
- Applications to dozens of conferences over the course of a single year to present their current work
- Sending paper drafts to discussants on time
- Preparing slides for presentations
- Submitting grand deliverables

Managing this manually is both time consuming and often leads to unwanted errors. I wrote a series of scripts ([remindR](https://github.com/clandinq/remindr)) to help project managers, researchers, research assistants and students keep track of deadlines related to academic projects. This system can send out four types of reminders:
1.	Future conference reminders. These are reminders to check if future conferences have announced details that would allow to track them (deadlines, submission links, and descriptions).
2.	Conference deadlines. Reminders to submit papers or abstracts to conferences.
3.	Upcoming presentations. Reminders for upcoming presentations, including slide submission deadlines.
4.	Grant deadlines. This can be useful both when applying for grants and when submitting grant deliverables.

Follow the instructions on the repo to set up remindR in your computer. The system is easy to set up, works with Mac OS X and Windows, and can be constantly modified when we???re notified of new deadlines. Please confirm with Sean / other PIs whenever you add a deadline to one of the lists. Also, it is important to keep track of the log to see that the system is working smoothly, and raise an issue on GitHub whenever there is a coding issue.

# 2. Keeping files organized
## i. Working with GitHub
GitHub is worked to keep facilitate sharing results and scripts with PIs and other research assistants, ensuring reproducibility of code, and having an up-to-date backup of current work, along with version control.
### Setting up a new repo on GitHub and cloning locally
1. Create new repo on GitHub, including a template .gitignore file. Modify .gitignore file on GitHub to include additional folders and files to exclude from updates: documents, data and certain file types.
2. Type the following commands in terminal:
    1. Change to directory where repo will be cloned 
        ```
        cd work
        ``` 
    2. Clone repo
        ```
        git clone https://github.com/user123/myproject
        ```

### Setting up an existing repo on the server or a new computer
KLC folders should be set up using Github (as if they were additional computers), so it???s easy to keep track of changes and sync files between the server and your local computer.

#### If there is already a folder set up on the server or computer and that be linked to the GitHub project repo
Type the following commands in the terminal:
1. Change directory to the existing folder
    ```
    cd existing_folder
    ``` 
2. Initialize repo
    ```
    git init
    ``` 
3. Link to existing repo
    ```
    git remote add origin https://github.com/user123/myproject
    ``` 
4. Git fetch using personal access token instead of password (https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
    ```
    git fetch
    ``` 
5. Checkout (here substitute main for master if master is name of branch generated on Github).
    ```
    git checkout origin/main -ft
    ``` 

#### If there is no folder set up on the server/computer:
Type the following commands in the terminal:
1. Change to directory where repo will be cloned 
    ```
    cd work
    ``` 
2. Clone repo
    ```
    git clone https://github.com/user123/myproject
    ```

### Updating the GitHub repo
First, modify files locally. Then, type the following commands in the terminal:
1. Change directory to project folder
    ```
    cd work/myrepo
    ``` 
2. Add new and modified files
    ```
    git add .
    ``` 
3. Review added files
    ```
    git status
    ``` 
4. Commit files and add a message
    ```
    git commit -m ???This message describes what was changed in the current commit"
    ``` 
5. Get most up to date code from remote repo.
    ```
    git pull
    ```
6. Push changes to remote repo
    ```
    git push
    ```

## ii. Working with the Kellogg Linux Cluster (KLC) server
Processing of large datasets (dataset size approximating RAM size) should be done on KLC. The workflow is the following:
1. Write scripts locally and push to GitHub.
2. Upload raw files with FileZilla to KLC, update server with scripts using GitHub.
3. Update results produced in server with GitHub.

### Uploading files via FileZilla
You should only upload and download data (both raw and proceessed) via [FileZilla](https://filezilla-project.org/), and keep updated results and scripts using GitHub. To upload new files, you can input the following on FileZilla:
- **Host**: klc.ci.northwestern.edu
- **Username**: Your NetID
- **Password**: Password for your NetID
- **Port**: 22
To upload files, drag to the selected folder on the right pane. To download files, right click download.

### Accessing KLC
1.	If you???re not connected to a network at Northwestern, use [GlobalProtect](https://kb.northwestern.edu/page.php?id=94726) to connect via VPN.
2.	If you have a Mac, open the terminal. If you have Windows, first install Cygwin so that you can use Linux commands from the command line, then you can open the command line with Windows+R, type cmd, Enter.
3.	In the terminal or command line, type:
    ```
    ssh <netID>@klc.ci.northwestern.edu
    ```
4.	Enter the password you created for your netID.
5.	Now you should be connected to KLC. 

### Running scripts
Once you have (1) set up GitHub to work with the KLC folder, (2) uploaded necessary data files, and (3) updated scripts using GitHub, there are two ways to run scripts on the server:
#### Running files with a 00_run script and no visible output
This first version will generate logs and return the command line for other work.
```
cd path_of_project_folder
module load stata/14 # or module load R/4.0.3 [or latest; check what???s available with module avail R]
nohup R CMD BATCH --vanilla -q scripts/00_run.do logs/00_run.log & # Nohup is so that if you get logged out the script keeps running.
```
#### Running do files (Stata) with visible output
The second option will display the output on the terminal.
```
cd path_of_project_folder
module load stata/14
stata-mp
# Set base directory and relative file paths
do scripts/myscript.do
```

# 3. Coding best practices
## i. Working with eps figures
Working with .eps files is useful because of their high resolution and ability to modify them. However, Latex can only compile PDF files, so we must use the package `epstopdf` to convert files automatically to .eps when compiling. Sometimes, the `epstopdf` package will not generate a PDF file. The following steps have been useful to solve this issue:
1.  Use script [gen_figures.R](https://github.com/clandinq/ra_guide/blob/main/scripts/gen_figures.R) to make a list with all .eps files included in the folder /results/figures, and generate a .tex document with all of them.
2.  Force full typeset this document to convert all eps figures to PDF.
