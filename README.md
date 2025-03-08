<h1>JokesWebApp</h1>
<p>JokesWebApp is a simple ASP.NET Core web application that allows users to browse, add, and manage jokes. The application is built with ASP.NET Core MVC and provides a user-friendly interface for interacting with jokes.</p>
<p><strong>Features</strong></p>
<ul>
<li>Browse a collection of jokes</li>
<li>Add new jokes</li>
<li>Edit and delete existing jokes</li>
<li>Responsive UI for desktop and mobile</li>
</ul>
<p><strong>Technologies Used</strong></p>
<ul>
<li>ASP.NET Core MVC</li>
<li>Entity Framework Core (EF Core) for database management</li>
<li>SQLite / SQL Server for data storage</li>
<li>Bootstrap for frontend styling</li>
</ul>
<p><strong>Getting Started</strong></p>
<p><strong>Prerequisites</strong></p>
<p>Make sure you have the following installed:</p>
<ul>
<li><a href="https://dotnet.microsoft.com/download/dotnet/6.0">.NET 6 SDK</a></li>
<li><a href="https://visualstudio.microsoft.com/">Visual Studio</a> or <a href="https://code.visualstudio.com/">VS Code</a></li>
<li>SQL Server / SQLite (optional, depending on configuration)</li>
</ul>
<p><strong>Installation</strong></p>
<ol start="1">
<li>Clone the repository:</li>
<li>Git clone https://github.com/yourusername/JokesWebApp.git</li>
<li>cd JokesWebApp</li>
<li>Install dependencies:</li>
<li>dotnet restore</li>
<li>Update the database:</li>
<li>dotnet ef database update</li>
<li>Run the application:</li>
<li>dotnet run</li>
<li>Open your browser and navigate to http://localhost:5000.</li>
</ol>
<p><strong>Usage</strong></p>
<ul>
<li>Click on "Add Joke" to submit a new joke.</li>
<li>Click on a joke to view details.</li>
<li>Edit or delete jokes as needed.</li>
</ul>
<p><strong>Database Configuration</strong></p>
<p>By default, the application uses SQLite. To change to SQL Server, modify appsettings.json:</p>
<p>"ConnectionStrings": {</p>
<p>&nbsp; "DefaultConnection": "Server=your_server;Database=JokesDB;Trusted_Connection=True;"</p>
<p>}</p>
<p>Run the following command to apply changes:</p>
<p>dotnet ef migrations add InitialCreate</p>
<p><strong>Contributing</strong></p>
<ol>
<li>Fork the repository</li>
<li>Create a new branch (git checkout -b feature-branch)</li>
<li>Commit your changes (git commit -m 'Add new feature')</li>
<li>Push to the branch (git push origin feature-branch)</li>
<li>Open a Pull Request</li>
</ol>
<p><strong>Contact</strong></p>
<p>For any inquiries or issues, feel free to open an issue or reach out via email at danevskimetodija5@gmail.com</p>
<p>&nbsp;</p>
