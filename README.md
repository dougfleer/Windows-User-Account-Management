<h1>Windows User Account Management Walkthrough</h1>
<br />
<center><img src="https://pentagram-production.imgix.net/ea053844-c063-4130-9425-4a193f82e1e3/ps_windows_01.jpg?rect=67%2C364%2C1665%2C1040&w=1500&fit=crop&fm=jpg&q=70&auto=format&h=935" height="250px"></img></center>
<br />
<h2>Summary</h2>
<p>
This project demonstrates how to manage local user accounts on a Windows 10 system. It covers adding, editing, and deleting user accounts using both graphical tools and the Command Prompt. This walkthrough is an essential guide for IT professionals and help desk technicians.
</p>

<h2>Features</h2>
<ul>
  <li>Add new local user accounts.</li>
  <li>Edit existing user accounts (e.g., update names, group memberships).</li>
  <li>Delete user accounts.</li>
  <li>Use the Command Prompt for user account management.</li>
</ul>

<h2>Instructions</h2>

<h3>Adding a User (Graphical)</h3>
<ol>
  <li>Open the "Run" dialog box (<code>Windows Key + R</code>) and type <code>lusrmgr.msc</code>. Press <strong>Enter</strong>.</li>
  <li>In the left pane, click on <strong>Users</strong>.</li>
  <li>Right-click anywhere in the right pane and select <strong>New User</strong>.</li>
  <li>Fill in the following fields:
    <ul>
      <li>Username</li>
      <li>Full Name</li>
      <li>Description (Optional)</li>
      <li>Password</li>
    </ul>
  </li>
  <li>(Optional) Uncheck <strong>User must change password at next logon</strong>.</li>
  <li>Click <strong>Create</strong>.</li>
</ol>
<img src="Screenshots/Add_User.png" alt="Add User Step" />

<h3>Modifying a User</h3>
<ol>
  <li>In the <strong>Users</strong> section, locate the user to edit.</li>
  <li>Right-click the user and select <strong>Properties</strong>.</li>
  <li>Update fields like:
    <ul>
      <li>Full Name</li>
      <li>Group Memberships</li>
      <li>Enable/Disable Account</li>
    </ul>
  </li>
  <li>Click <strong>OK</strong> to save your changes.</li>
</ol>
<img src="Screenshots/Edit_User.png" alt="Edit User Step" />

<h3>Deleting a User</h3>
<ol>
  <li>In the <strong>Users</strong> section, locate the user to delete.</li>
  <li>Right-click the user and select <strong>Delete</strong>.</li>
  <li>Confirm the action when prompted.</li>
</ol>
<img src="Screenshots/Delete_User.png" alt="Delete User Step" />

<h3>Using Command Prompt</h3>
<ol>
  <li>Open Command Prompt as <strong>Administrator</strong>.</li>
  <li>Use the following commands:
    <ul>
      <li><strong>Add a user:</strong>
        <pre><code>net user NewUserName Password123 /add</code></pre>
      </li>
      <li><strong>Modify a user:</strong>
        <pre><code>net user NewUserName NewPassword</code></pre>
      </li>
      <li><strong>Delete a user:</strong>
        <pre><code>net user NewUserName /delete</code></pre>
      </li>
    </ul>
  </li>
</ol>
<img src="Screenshots/Command_Prompt_User_Management.png" alt="Command Prompt User Management" />

<h2>Conclusion</h2>
<p>
This walkthrough provides a clear, step-by-step guide to managing local user accounts on Windows 10, a vital skill for IT and help desk roles.
</p>
