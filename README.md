# Attendance recorder

version: 1.0.0
released on 29 Dec 2020

### Features
The system has the following major features

  - Add/modify records and users
  - Manage records, users and event
  - Get statistics and data output
  - Logging of all write operation

### Operations
  - #### Add record
    - On the main page, **choose the cell**
    - Select an **event**
    - Select the participating members and press ***add record***
    - Note: description is only for future reference only
    - Note2: The **!** symbol also signifies that no record for the selected cell of that particular event. Tick symbol means otherwise

  - #### Add member, cell, event
    - ##### Add **Member**
      - Go to ***Admin*** page
      - In the choose a cell section
      - Select a cell and enter the new member name
      - Press ***Add a member***
    - ##### Add **Event**
      - Go to ***Admin*** page
      - In the Add event section
      - Enter the function name
      - Select the function date
      - Toggle the switch to make the event compulsory/optional
      - Press ***Add a cell***
    - ##### Add **Cell**
      - Go to ***Admin*** page
      - In the Admin functions session
      - Long press modify cell information
      - Enter new Cell name in add new cell
      - Press ***Add new cell***
      - *Note that cells can have same name, but is strongly advised to disable one first. This is meant for reusing old cell names if needed*
    - Note: all names, cells and events shouldn't contain a comma ',' as it will affect the csv file output
    - Note 2: Optional events means it will not appear in statistic
    
  - #### Modify Cell
    - Go to **Admin** page
    - Long press **modify cell information**
    - In the *Change cell Name and Status* section select the Cell to modify
    - Toggle the cell active/inactive and change the name
    - Press *Confirm* to make the change
    - *Note: Inactive cell means it will not show up when adding record*

  - #### Modify User
    - ##### Change **user info**
      - Go to ***Admin*** page
      - In the Admin functions session
      - Long press **modify user info**
      - Select the cell and press on the user
      - Edit the info and press *confirm*
    - ##### Change **user cells**
      - Go to ***Admin*** page
      - In the Admin functions session
      - Long press **Change users cells**
      - Select the destination cell
      - Select all the users that you want to move to the destination cell
      - Press *Move* to move the users
    - *Note: Inactive user means it will not show up when adding record, but will still show up in statistic page if relevant record exists*

  - #### Modify Event
    - Go to **Admin** page on main page
    - ##### **Edit** event
      - Long press **Edit/remove** event
      - **Tap** on the event to change the event name/date/optional
    - ##### **Remove** event
      - Same as above but long press the event to remove it
    - ##### **Recover** event
      - Select **Recover an event**
      - Long press an event to recover it
      - Note: Participation data will also be recovered

  - #### Search Record
    - Select **Records** on the main page
    - Enter date in the App Bar to narrow down search results (optional)
    - **!** symbol means some cells has not fill in the record yet, it will be a tick symbol otherwise
    - Press on the event to see participants from each cell

  - #### Statistics
    - Go to **Statistics** page on main page
    - ##### View **Individual statistic**
      - Select start and end date
      - **Move the slider** to the correct percentage/number of required participation
      - **Result** will show all the users in each cell that satisfies the requirement
      - **View by cell** will show individual users that satisfies the requirement and their corresponding participation count

    - ##### View **Statistic by date**
      - All events will be organised in years and months
      - Year and month average can be viewed
      - Individual total of each cell and overall total can also be viewed
    - *Note: Inactive user means it will not show up when adding record*

  - #### Export Excel/CSV data
    - Go to **Admin** page
    - Select the desired data format
    - Detail info of different format below

  ### Attendance data with cell data on y axis
  
  Date | Event | Event optional | Cell | Participants
  ------------- | ------------- | --| -- | -- |
  Date 1 | Event name | True/false | Cell 1 | participant 1 | participant 2 | ... 
  | | | | Cell 2 | participant 1 | participant 2 | ...
  | | | | Cell 3 | participant 1 | participant 2 | ...
  Date 2 | Event name 2 | True/false | Cell 1 | participant 1 | participant 2 | ... 
  | | | | Cell 2 | participant 1 | participant 2 | ...
  | | | | Cell 3 | participant 1 | participant 2 | ...
  
  ### Attendance data with cell data on x axis
  
  Date | Event | Event optional | Cell name 1 | Cell name 2 | Cell name 3 | ...
  ------------- | ------------- | -------------| ---------- | ----------- | ------ | ------ |
  Date 1 | Event name 1 | True/false | participant1;participant2;participant3 | | participant 1 | 
  Date 2 | Event name 2 | True/false | participant1;participant2 | participant 1 | participant 1;participant2

### Feedback
Let me know directly if you have any feature request and bugs encountered.
Or submit a feature request/report a bug encountered via this google form: https://forms.gle/3erhUSFMeaYpUuWU7.

