<!--
  CUSTOMISING THIS README
  - Colours used everywhere: #8b5cf6 (purple), #3b82f6 (blue), #161b22 (charcoal), #0d1117 (black)
  - Search for "TODO" to find every placeholder.
  - Images in ./assets are hosted in this repo, so they never depend on third-party servers.
-->

<div align="center">

<img src="./assets/banner.svg" width="100%" alt="Terminal-style banner: Vidya Kumari. Building software. Thinking like an attacker." />

<br />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3200&pause=1200&color=A78BFA&center=true&vCenter=true&repeat=true&width=620&height=36&lines=Building+full-stack+apps+with+Python+and+FastAPI;Scanning+repositories+for+leaked+credentials;Studying+SOC+and+blue-team+workflows;Writing+up+web+security+labs+on+SecVidya" alt="Rotating line: building full-stack apps with Python and FastAPI, scanning repositories for leaked credentials, studying SOC and blue-team workflows, writing up web security labs on SecVidya." />

<br />

<img src="https://img.shields.io/badge/DSCE-ISE_2024--2028-8b5cf6?style=flat-square&labelColor=161b22" alt="Dayananda Sagar College of Engineering, Information Science, 2024 to 2028" />
<img src="https://img.shields.io/badge/ACM-Member-3b82f6?style=flat-square&labelColor=161b22" alt="ACM member" />
<img src="https://img.shields.io/badge/Based_in-Bengaluru-8b5cf6?style=flat-square&labelColor=161b22" alt="Based in Bengaluru, India" />

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/about`

I'm an Information Science and Engineering student at **Dayananda Sagar College of Engineering, Bengaluru**. I build full-stack projects in Python and FastAPI, and I'm most interested in the part of software people tend to skip: how it breaks, and how to catch that early.

I learn by shipping something, attacking it with tools like Burp Suite and PortSwigger labs, and writing up what I found on my blog. I'm an **ACM member** and take part in the campus tech community.

```yaml
# vidya.yml
name:      Vidya Kumari
studying:  B.E. Information Science & Engineering @ DSCE (2024-2028)
building:  [RepoSentinel, InvestigatorCopilot]
focus:     [web app security, SOC / blue team, backend APIs]
community: ACM
learns_by: build -> break -> write it up
```

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/stack`

<!-- Only technologies listed on my resume / used in my projects. Add or remove ids at skillicons.dev -->
<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=java,py,cpp,js,html,css&theme=dark" alt="Java, Python, C++, JavaScript, HTML, CSS" />
      <img src="https://img.shields.io/badge/SQL-161b22?style=flat-square&labelColor=161b22&color=8b5cf6" alt="SQL" />
    </td>
  </tr>
  <tr>
    <td><b>Backend &amp; Web</b></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,bootstrap,tomcat,maven&theme=dark" alt="FastAPI, Bootstrap, Apache Tomcat, Maven" /></td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql&theme=dark" alt="PostgreSQL, MySQL" /></td>
  </tr>
  <tr>
    <td><b>Data &amp; ML</b></td>
    <td><img src="https://skillicons.dev/icons?i=sklearn,pandas,numpy&theme=dark" alt="scikit-learn, pandas, NumPy" /></td>
  </tr>
  <tr>
    <td><b>Tools &amp; Cloud</b></td>
    <td><img src="https://skillicons.dev/icons?i=git,github,vscode,linux,aws&theme=dark" alt="Git, GitHub, VS Code, Linux, AWS" /></td>
  </tr>
  <tr>
    <td><b>Security &amp; SOC</b></td>
    <td>
      <img src="https://img.shields.io/badge/Burp_Suite-161b22?style=flat-square&logo=burpsuite&logoColor=a78bfa" alt="Burp Suite" />
      <img src="https://img.shields.io/badge/OWASP_ZAP-161b22?style=flat-square&logo=owasp&logoColor=a78bfa" alt="OWASP ZAP" />
      <img src="https://img.shields.io/badge/Splunk-161b22?style=flat-square&logo=splunk&logoColor=a78bfa" alt="Splunk" />
      <img src="https://img.shields.io/badge/Elastic_Stack-161b22?style=flat-square&logo=elastic&logoColor=a78bfa" alt="Elastic Stack and Kibana" />
    </td>
  </tr>
  <tr>
    <td><b>Practice</b></td>
    <td>
      <img src="https://img.shields.io/badge/TryHackMe-Top_4%25-161b22?style=flat-square&logo=tryhackme&logoColor=60a5fa" alt="TryHackMe, top 4 percent" />
      <img src="https://img.shields.io/badge/PortSwigger-Web_Security_Academy-161b22?style=flat-square&logoColor=60a5fa" alt="PortSwigger Web Security Academy" />
      <img src="https://img.shields.io/badge/LeetCode-161b22?style=flat-square&logo=leetcode&logoColor=60a5fa" alt="LeetCode" />
    </td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/projects`

<!--
  TO ADD A PROJECT: copy one <td> block below, change the name, links, description, and stack.
  Each <tr> holds two projects. Keep descriptions to 2-3 lines.
-->
<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/vidya235252-crypto/credential-scanner">RepoSentinel</a></h3>
      <sub>Credential / secret leak scanner &nbsp;·&nbsp; <a href="https://credential-scanner.onrender.com">Live demo</a></sub>
      <p>Scans GitHub repositories for exposed API keys, AWS keys, Slack tokens and private keys using regex patterns plus Shannon-entropy analysis for unrecognised formats. GitHub OAuth and JWT auth, per-user scan history, explainable confidence and risk scores with remediation suggestions, and live scan progress over WebSockets.</p>
      <sub><code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>WebSockets</code> <code>OAuth</code> <code>JWT</code></sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/vidya235252-crypto/investigator-copilot">InvestigatorCopilot</a></h3>
      <sub>AI fraud investigation assistant &nbsp;·&nbsp; Razorpay AI Buildathon 2026</sub>
      <p>Investigates account-takeover-driven payment abuse. A weighted-rules and scikit-learn risk engine feeds an evidence-grounded LLM investigator, with an incident timeline and analyst dashboard. <b>1.00 precision, 0.925 recall, 0.961 F1</b> on a held-out set, and <b>45.8% less</b> investigator reading time than raw event logs.</p>
      <sub><code>Python</code> <code>FastAPI</code> <code>scikit-learn</code> <code>pandas</code> <code>SQLite</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/vidya235252-crypto/Rideshare-Carpool">RideShare</a></h3>
      <sub>Carpooling coordinator</sub>
      <p>Create, manage and join shared rides, with booking, cancellation and a live map built on Leaflet.js. REST API backend with CRUD operations on a relational MySQL schema.</p>
      <sub><code>FastAPI</code> <code>MySQL</code> <code>JavaScript</code> <code>Leaflet.js</code></sub>
    </td>
    <td width="50%" valign="top">
      <h3>Also on GitHub</h3>
      <p>
        <a href="https://github.com/vidya235252-crypto/portfolio-3d">portfolio-3d</a> (JavaScript)<br />
        <a href="https://github.com/vidya235252-crypto/bangalore-pincode-explorer">bangalore-pincode-explorer</a> (CSS)<br />
        <a href="https://github.com/vidya235252-crypto/placement-week-scheduler">placement-week-scheduler</a> (Python)
      </p>
      <sub><a href="https://github.com/vidya235252-crypto?tab=repositories">All repositories →</a></sub>
    </td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/exploring`

- **SOC and blue-team workflows**: SIEM, log analysis, and detection basics with Elastic Stack and Splunk
- **Cloud security on AWS**: IAM and access management fundamentals
- **Web application security**: working through PortSwigger Web Security Academy labs and publishing the writeups
- **Evidence-grounded LLM systems**: making AI-assisted investigation explainable instead of a black box
<!-- TODO: add or swap items as your focus changes -->

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/community`

<table>
  <tr>
    <td width="30%" valign="top"><b>Community</b></td>
    <td>
      <b>ACM</b>, member <!-- TODO: add your chapter and any role, e.g. "DSCE ACM Student Chapter" -->
      <br />Stage Management Club, DSCE (2025)
      <br />E-Summit 2024, volunteer (Decor and Logistics; supported the Hackathon and Mock IPL Auction)
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Hackathons</b></td>
    <td>
      Razorpay AI Buildathon 2026, AI Risk Manager track: built InvestigatorCopilot
      <!-- TODO: add the result or any other hackathon -->
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Recognition</b></td>
    <td>
      TryHackMe, top 4%
      <!-- TODO: add awards, ranks, or open-source contributions -->
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Certifications</b></td>
    <td>
      TryHackMe SOC Level 1 Learning Path (Aug 2026)<br />
      TryHackMe Pre-Security Learning Path (Jun 2026)<br />
      AWS Educate, Getting Started with Security (Jul 2026) <!-- TODO: link your Credly badge -->
      <br />Splunk, Intro to Splunk and Using Fields (Aug 2026)<br />
      Cyber Security and Awareness Skill Development Program, Heartiestmind Technologies at DSCE (Mar 2026)
    </td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/stats`

<!--
  These cards are generated by .github/workflows/profile-summary-cards.yml and committed to this repo,
  so they load from GitHub itself. Run the workflow once (Actions tab -> Run workflow) before they appear.

  TEMPORARY FALLBACK (live API, works with no setup, may be slower or rate-limited):
  https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=vidya235252-crypto&theme=tokyonight
  https://github-profile-summary-cards.vercel.app/api/cards/stats?username=vidya235252-crypto&theme=tokyonight
  https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=vidya235252-crypto&theme=tokyonight&utcOffset=5
-->
<div align="center">

<img src="https://raw.githubusercontent.com/vidya235252-crypto/vidya235252-crypto/main/profile-summary-card-output/tokyonight/0-profile-details.svg" width="100%" alt="GitHub profile summary: followers, contributions and activity overview" />

<img src="https://raw.githubusercontent.com/vidya235252-crypto/vidya235252-crypto/main/profile-summary-card-output/tokyonight/3-stats.svg" width="49%" alt="GitHub stats: stars, commits, pull requests and issues" />
<img src="https://raw.githubusercontent.com/vidya235252-crypto/vidya235252-crypto/main/profile-summary-card-output/tokyonight/2-most-commit-language.svg" width="49%" alt="Languages with the most commits" />

<img src="https://raw.githubusercontent.com/vidya235252-crypto/vidya235252-crypto/main/profile-summary-card-output/tokyonight/1-repos-per-language.svg" width="49%" alt="Repositories per language" />
<img src="https://raw.githubusercontent.com/vidya235252-crypto/vidya235252-crypto/main/profile-summary-card-output/tokyonight/4-productive-time.svg" width="49%" alt="Most productive time of day by commits" />

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## `~/connect`

<div align="center">

<a href="https://www.linkedin.com/in/vidya2508"><img src="https://img.shields.io/badge/LinkedIn-vidya2508-8b5cf6?style=for-the-badge&labelColor=161b22" alt="LinkedIn profile: vidya2508" /></a>
<a href="mailto:vidya235252@gmail.com"><img src="https://img.shields.io/badge/Email-vidya235252@gmail.com-3b82f6?style=for-the-badge&labelColor=161b22" alt="Send an email to vidya235252@gmail.com" /></a>
<br />
<a href="https://portfolio-vidya20.vercel.app"><img src="https://img.shields.io/badge/Portfolio-portfolio--vidya20-8b5cf6?style=for-the-badge&labelColor=161b22" alt="Portfolio website" /></a>
<a href="https://secvidya.hashnode.dev"><img src="https://img.shields.io/badge/Blog-SecVidya-3b82f6?style=for-the-badge&labelColor=161b22" alt="SecVidya, my cybersecurity blog on Hashnode" /></a>
<!-- TODO (optional): add TryHackMe and LeetCode profile links in the same format, e.g.
<a href="YOUR_TRYHACKME_PROFILE_URL"><img src="https://img.shields.io/badge/TryHackMe-profile-8b5cf6?style=for-the-badge&labelColor=161b22" alt="TryHackMe profile" /></a>
-->

<br /><br />

<sub><code>build → break → write it up</code></sub>

</div>
