<h1>File Integrity Monitor</h1>


<h2>Description</h2>
<b>The PowerShell script in this repository is responsible for creating file hashes stored in a baseline.txt file. This file will be updated and checked while the script is running for file modification/deletion/creation. If any events trigger, then the script will notify the user of what has been changed.
</b>
<br />
<br />
The script has two options: Create a new baseline or Begin monitoring files saved with baseline. When creating a new baseline, the script will create a hash of every file within the user-given path. These hashes are stored in the baseline.txt file to refer back to when monitoring.
<br />
<br />

<p align="center">
<img src="https://github.com/4am-walking/File-Integrity-Monitor/blob/main/Create%20Baseline.PNG" height="85%" width="85%" alt="Creating a new baseline file."/>
</p>

<br />
The second option monitors the user-given path for any modifications to the files under it. It can also monitor for new files. Whenever a change is made to the path, the script will output an alert to the user notifying what change has been made.
<br />
<br />

<p align="center">
<img src="https://github.com/4am-walking/File-Integrity-Monitor/blob/main/Checking%20Integrity.png" height="85%" width="85%" alt="Monitoring baseline file."/>
</p>

<h2>Languages Used</h2>

- <b>PowerShell:</b> Creation of baseline and monitoring.
