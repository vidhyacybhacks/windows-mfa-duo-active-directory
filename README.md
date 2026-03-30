<h1>🔐 Windows Login with 2-Step Authentication using Duo Security</h1>
<h2>🔐 Project Overview</h2>
<p>A hands-on cybersecurity lab demonstrating how to secure Windows login using Multi-Factor Authentication (MFA) with Duo Security integrated into Active Directory.</p>
<p>This setup simulates an enterprise authentication system where users must verify their identity using both a password and a second authentication factor such as a mobile push notification or OTP.</p>
<hr>
<h2>🎯 Objective</h2>
<ul>
<li>Implement Multi-Factor Authentication (MFA) in a domain-based environment</li>
<li>Integrate Active Directory with Duo Security</li>
<li>Simulate enterprise-level Windows login security</li>
<li>Prevent unauthorized access using 2-step authentication</li>
</ul>
<hr>
<h2>🛠️ Technologies Used</h2>
<ul>
<li>Active Directory</li>
<li>Duo Security</li>
<li>Windows Server 2019</li>
<li>Windows 10</li>
<li>VMware / VirtualBox</li>
</ul>
<hr>
<h2>🏗️ Architecture</h2>
<p>The system consists of:</p>
<ul>
<li>Domain Controller (Windows Server)</li>
<li>Client Machine (Windows 10)</li>
<li>Duo Security MFA Integration</li>
</ul>
<h3>Authentication Flow</h3>
<ol>
<li>User enters username and password</li>
<li>Active Directory verifies credentials</li>
<li>Duo Security triggers second-factor authentication</li>
<li>User approves login via mobile (Duo Push / OTP)</li>
<li>Access is granted</li>
</ol>
<hr>
<h2>⚙️ Implementation Overview</h2>
<ol>
<li>Setup Active Directory Domain Controller</li>
<li>Created users in Active Directory</li>
<li>Joined client machine to domain</li>
<li>Installed Duo Authentication for Windows Logon</li>
<li>Configured MFA using Duo Admin Panel</li>
<li>Tested login using Duo Push / OTP</li>
</ol>
<hr>
<h2>✅ Results</h2>
<ul>
<li>MFA successfully integrated with Windows login</li>
<li>Unauthorized access without second factor blocked</li>
<li>Secure authentication system implemented</li>
<li>Enterprise-level login simulation achieved</li>
</ul>
<hr>
<h2>⚠️ Challenges Faced</h2>
<ul>
<li>DNS issues during domain join</li>
<li>Incorrect login format (DOMAIN\username)</li>
<li>Duo configuration errors</li>
<li>Internet dependency for MFA</li>
<li>Time synchronization issues</li>
</ul>
<hr>
<h2>🧾 Conclusion</h2>
<p>The implementation of Multi-Factor Authentication (MFA) using Active Directory and Duo Security significantly improves Windows login security.</p>
<p>By adding a second layer of authentication, the system becomes more resistant to unauthorized access, even if passwords are compromised. This setup reflects real-world enterprise security practices and highlights the importance of MFA in modern cybersecurity.</p>
<hr>
<h2>⚠️ Disclaimer</h2>
<p>This project was implemented in a personal virtual lab environment for educational purposes. No production systems or real organizational data were used.</p>
<hr>
<h2>🚀 Future Scope</h2>
<ul>
<li>Integrate MFA with VPN systems</li>
<li>Extend to cloud environments (Azure AD)</li>
<li>Implement hardware-based authentication</li>
<li>Apply MFA to web applications</li>
</ul>
