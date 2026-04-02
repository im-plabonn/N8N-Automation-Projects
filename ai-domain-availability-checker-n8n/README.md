<h1>AI Domain Availability Checker using n8n + GPT</h1>

<p>
This project is an AI-powered workflow automation that checks .com domain availability 
for a given business name and provides intelligent feedback including comment, status, 
and reason. The automation helps validate brand names quickly before using them.
</p>

<hr/>

<h2>🎯 Main Purpose</h2>

<p>
The main purpose of this project is to automate the process of validating business names 
by checking domain availability first and then using AI to evaluate the name quality.
</p>

<ul>
<li>Avoid choosing names with unavailable domains</li>
<li>Save time during brand name selection</li>
<li>Get AI-based feedback automatically</li>
<li>Create structured evaluation for each name</li>
<li>Build a reusable automation workflow</li>
</ul>

<hr/>

<h2>⚙️ What This Automation Does</h2>

<ol>
<li>User provides a business name</li>
<li>The workflow generates a .com domain</li>
<li>System checks domain availability using API</li>
<li>If domain is not available → returns "Not Available"</li>
<li>If domain is available → AI evaluates the name</li>
<li>AI generates comment, status, and reason</li>
<li>Results are stored in Google Sheets</li>
</ol>

<hr/>

<h2>🧠 Example Output</h2>

<pre>
Business Name: Plabon

Domain: Available

Comment: Memorable personal brand but slightly long
Status: Recommended
Reason: Unique and brandable
</pre>

<hr/>

<h2>🔄 Workflow Overview</h2>

<pre>
User Input
   ↓
Generate .com Domain
   ↓
Check Domain Availability
   ↓
IF Available
   ↓
Send to AI
   ↓
Generate Comment + Status + Reason
   ↓
Save to Google Sheets
</pre>

<hr/>

<h2>🛠️ Technologies Used</h2>

<ul>
<li>n8n (Workflow Automation)</li>
<li>OpenAI GPT-4o (AI Feedback)</li>
<li>Google Sheets (Data Storage)</li>
<li>HTTP API (Domain Availability Check)</li>
<li>Conditional Logic (IF Node)</li>
</ul>

<hr/>

<h2>📦 Requirements</h2>

<ul>
<li>n8n instance (Cloud or Self-hosted)</li>
<li>OpenAI API Key</li>
<li>Google Sheets account</li>
<li>Domain availability API</li>
</ul>

<hr/>

<h2>🚀 Features</h2>

<ul>
<li>Automatic .com domain check</li>
<li>AI-generated comment</li>
<li>Status recommendation</li>
<li>Reason explanation</li>
<li>Conditional automation logic</li>
<li>Google Sheets integration</li>
<li>Beginner-friendly workflow</li>
<li>Structured output</li>
</ul>

<hr/>

<h2>💡 Use Cases</h2>

<ul>
<li>Startup name validation</li>
<li>Brand name checking</li>
<li>Personal brand evaluation</li>
<li>Domain-first naming workflow</li>
<li>AI automation demonstration</li>
</ul>

<hr/>

<h2>📈 Why This Project</h2>

<p>
Many people choose business names without checking domain availability. 
Later they find that the domain is already taken. This automation solves 
that problem by checking availability first and only evaluating usable names.
</p>

<hr/>

<h2>🧪 How To Use</h2>

<ol>
<li>Import the n8n workflow</li>
<li>Add your OpenAI API key</li>
<li>Connect Google Sheets</li>
<li>Run the workflow</li>
<li>Enter business name</li>
<li>Get AI feedback automatically</li>
</ol>

<hr/>

<h2>Learning Outcome</h2>

<ul>
<li>AI workflow automation</li>
<li>API integration</li>
<li>Conditional logic design</li>
<li>Google Sheets automation</li>
<li>Structured AI output</li>
<li>No-code automation architecture</li>
</ul>

<hr/>

<h2>👨‍💻 Author</h2>

<p>
Plabon Rahman <br/>
AI Automation Builder <br/>
Workflow Automation Enthusiast
</p>
