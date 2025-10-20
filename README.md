<h2 align="center">🚀 My Cybersecurity Projects & Demos</h2>
<p align="center">
  A collection of my hands-on projects, from AI-powered scanning to low-level reverse engineering.
  <br>
  <strong><a href="https://www.linkedin.com/in/nawaz-muztaba/">Connect with me on LinkedIn</a></strong>
  <br>
  (Click any thumbnail to see the full post)
</p>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_ai-powered-vapt-scanner-1-orchestration-activity-7385865449676238848-iu2M">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/AI%20VAPT.png?raw=true" alt="AI VAPT Scanner" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>AI-Powered VAPT Scanner ⚡</h3>
      <p>A full-stack VAPT tool that orchestrates scanners (Subfinder, Nmap, Nuclei), parses the results, and uses Google Gemini to analyze and generate a professional security report.</p>
      <details>
        <summary><b>Click to see Key Features</b></summary>
        <ul>
          <li><b>Orchestration ⚙️:</b> Runs Subfinder, HTTPX, Nmap, Nikto, & Nuclei in parallel to save time.</li>
          <li><b>Parsing 📑:</b> Organizes all messy tool outputs into a single, clean JSON file.</li>
          <li><b>AI Analysis 🧠:</b> Sends structured JSON to the Google Gemini API for expert-level analysis and automated report generation.</li>
        </ul>
      </details>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_ai-powered-vapt-scanner-1-orchestration-activity-7385865449676238848-iu2M">
        <b>📄 View Full Post & Details on LinkedIn</b>
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_cybersecurity-securityawareness-phishing-activity-7382039746589585409-1rsb">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/PHISHING.png?raw=true" alt="Phishing Demo" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>How Your Phone is Easily Hacked (Phishing Demo) ‼️</h3>
      <p>An ethical, educational demonstration of a sophisticated phishing attack in a controlled lab to show what to *really* look for to expose a fake website.</p>
      <details>
        <summary><b>Click to see Key Learnings</b></summary>
        <ul>
          <li>🔹 How quickly a perfect replica of a login page can be created.</li>
          <li>🔹 The #1 giveaway that instantly exposes a fake website.</li>
          <li>🔹 Why the HTTPS lock icon 🔒 no longer means a site is safe.</li>
        </ul>
      </details>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_cybersecurity-securityawareness-phishing-activity-7382039746589585409-1rsb">
        <b>📄 View Full Post & Details on LinkedIn</b>
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_cybersecurity-reverseengineering-ethicalhacking-activity-7377998171332960256-kwbc">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/ONE%20LINE%20HACKED.png?raw=true" alt="Reverse Engineering Project" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>Forget the Password. Let's Rewrite the Rules. 💥</h3>
      <p>A reverse engineering project using IDA Pro to analyze a password-check program. Instead of guessing the password, I patched the program's logic to bypass the check entirely.</p>
      <details>
        <summary><b>Click to see The Hack</b></summary>
        <ul>
          <li><b>Analysis:</b> Used IDA Pro to find the exact line of code that checks the password.</li>
          <li><b>The Logic:</b> The original rule was: "If the password is WRONG, jump to 'Access Denied'."</li>
          <li><b>The Patch:</b> I changed the rule to: "Only if the password is RIGHT, jump to 'Access Denied'."</li>
          <li><b>Result:</b> Every wrong password now grants access. ✅</li>
        </ul>
      </details>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_cybersecurity-reverseengineering-ethicalhacking-activity-7377998171332960256-kwbc">
        <b>📄 View Full Post & Details on LinkedIn</b>
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_cybersecurity-malwareanalysis-threathunting-activity-7373157203047952384-VJLK"> 
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/MALWARE%20ANALYSIS.png?raw=true" alt="Malware Analysis Project" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>Malware Analysis: Dismantling an Executable 🛑</h3>
      <p>A deep-dive analysis of a malicious executable, tracing its behavior from initial deception and persistence (Registry changes) to live C2 communication.</p>
      <details>
        <summary><b>Click to see Key Discoveries</b></summary>
        <ul>
          <li><b>Static Analysis:</b> Found imports for <code>wininet.dll</code> (internet access) and deceptive strings.</li>
          <li><b>System Takeover:</b> Used Process Monitor to track 48 Registry changes for persistence.</li>
          <li><b>Live Behavior:</b> Watched it spawn new processes and interact with critical system files in real-time.</li>
        </ul>
      </details>
      <br>
      <a href="https://lnkd.in/dXyXHYqv"><b>📄 View Full Technical Report</b></a>
      <br>
      <a href="https://lnkd.in/dJnFYvWT"><b>📦 View Malware Sample (Use in VM!)</b></a>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_cybersecurity-malwareanalysis-threathunting-activity-7373157203047952384-VJLK"><b>🔗 View Original Post on LinkedIn</b></a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_redteam-pentesting-hacking-activity-7372902542424313856-lYnK">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/UNDETECTABLE.png?raw=true" alt="Undetectable Payload" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>Undetectable Payload Creation (Ethical Hacking) 💀</h3>
      <p>This isn't just running a command; it's understanding the craft. Taking a standard executable and reforging it into a custom implant for remote access.</p>
      <details>
        <summary><b>Click to see Project Focus</b></summary>
        <ul>
          <li><b>Red Teaming:</b> Simulating advanced attacker techniques.</li>
          <li><b>Evasion:</b> Understanding how payloads are modified to avoid detection.</li>
          <li><b>Threat Hunting:</b> Learning what to look for to defend against such implants.</li>
        </ul>
      </details>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_redteam-pentesting-hacking-activity-7372902542424313856-lYnK">
        <b>📄 View Full Post & Details on LinkedIn</b>
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_androidsecurity-cybersecurity-kalilinux-activity-7372417305789693953-n9Ws">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/ANDROID%20APK.png?raw=true" alt="MobSF APK Analysis" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>Is Your Android App an Open Book? (MobSF Demo) 📖</h3>
      <p>A hands-on demonstration of using MobSF on Kali Linux to perform static and dynamic analysis on a vulnerable APK, hunting for hardcoded secrets and dangerous permissions.</p>
      <details>
        <summary><b>Click to see What I Uncovered</b></summary>
        <ul>
          <li>🕵️‍♂️ Critical red flags & security flaws.</li>
          <li>🚦 Dangerous permissions putting users at risk.</li>
          <li>🔑 Hardcoded secrets hidden in plain sight.</li>
        </ul>
      </details>
      <br>
      <a href="https.www.linkedin.com/posts/nawaz-muztaba_androidsecurity-cybersecurity-kalilinux-activity-7372417305789693953-n9Ws">
        <b>📄 View Full Post & Details on LinkedIn</b>
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_networksystemmkv-activity-7314634888438079488-gIbd">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/NETWORK.png?raw=true" alt="Firewall Internship Assignment" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>Internship Assignment: Network Security & Firewall Config 🔥</h3>
      <p>A hands-on assignment focusing on real-world network defense and firewall configuration using <b>Linux (iptables)</b>.</p>
      <details>
        <summary><b>Click to see Key Topics Covered</b></summary>
        <ul>
          <li>🔐 Network Security Fundamentals & Threat Types</li>
          <li>🛡️ Firewall Roles & Types (Software, Hardware, Cloud)</li>
          <li>💻 <b>Technical Demo (iptables):</b> Allowing/Blocking Ports</li>
          <li>🔎 <b>Technical Demo (iptables):</b> Filtering IP Addresses</li>
        </ul>
      </details>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_networksystemmkv-activity-7314634888438079488-gIbd">
        <b>📄 View Full Assignment on LinkedIn</b>
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border: 1px solid #30363d; border-radius: 8px; margin-bottom: 20px;">
  <tr>
    <td width="250px" valign="top" style="padding: 15px;">
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_01ddoszip-activity-7288693965216780289-Boa5">
        <img src="https://github.com/NawazMuztaba/NawazMuztaba/blob/main/DDOS.png?raw=true" alt="DDoS Attack Project" width="250px" style="border-radius: 5px;"/>
      </a>
    </td>
    <td valign="top" style="padding: 15px;">
      <h3>Impact of DDoS Attacks on Network Performance 🚀</h3>
      <p>A project involving DDoS simulations to analyze network impact (latency, CPU, packet loss) and implementing a hybrid mitigation strategy with ML-based anomaly detection.</p>
      <details>
        <summary><b>Click to see Key Details</b></summary>
        <ul>
          <li><b>Tools:</b> Linux CLI, Windows XP (monitoring), Python.</li>
          <li><b>Key Result:</b> Reduced packet loss by 40% post-mitigation.</li>
          <li><b>Strategy:</b> Combined ML anomaly detection with rate limiting.</li>
        </ul>
      </details>
      <br>
      <a href="https://www.linkedin.com/posts/nawaz-muztaba_01ddoszip-activity-7288693965216780289-Boa5">
        <b>📄 View Full Documentation & Video Demo</b>
      </a>
    </td>
  </tr>
</table>
