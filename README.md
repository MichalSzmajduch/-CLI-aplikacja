<h1>Phone Book App</h1>
<p>The Phone Book App allows you to manage a list of contacts by adding, displaying, removing, and fetching contact information.</p>
<h2>Features</h2>
<h3>Displaying the Contact List</h3>
<img src="/img/list.png" alt="display list">
<h3>Adding a Contact</h3>
<img src="/img/add.png" alt="adding contact">
<h3>Fetching a Contact</h3>
<img src="/img/find.png" alt="fetching contact">
<h3>Removing a Contact</h3>
<img src="/img/remove.png" alt="removing contact">
<h2>Usage</h2>
<p>Displaying the Contact List</p>
<ol>
<li>To display a list of all contacts, use the command:</li>
<li>node index.js --action list</li>
</ol>
<p>Adding a Contact</p>
<ol>
<li>To add a new contact, use the command:</li>
<li>node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22</li>
</ol>
<p>Deleting a Contact</p>
<ol>
<li>To remove a contact based on its ID, use the command:</li>
<li>node index.js --action remove --id " "</li>
</ol>
<p>Filtering Contacts</p>
<ol>
<li>To fetch detailed information about a specific contact, use the command along with its ID:</li>
<li>node index.js --action get --id " "</li>
</ol>
