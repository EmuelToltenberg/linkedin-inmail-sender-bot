# LinkedIn InMail Sender Bot

The **LinkedIn InMail Sender Bot** automates the process of sending personalized InMail messages on LinkedIn at scale. This tool enables businesses and recruiters to reach potential leads or candidates more efficiently without manual intervention, saving time while increasing outreach.


<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>

<p align="center">
  <a href="https://t.me/devpilot1" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/xvPWXJXCw7" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



## Introduction

This automation tool streamlines LinkedIn outreach by automating the sending of InMail messages to a list of targets. It allows users to quickly execute mass outreach campaigns, targeting individuals based on custom filters or job titles. By automating the repetitive task of messaging, it frees up time for users to focus on more strategic activities.

### Why Automating LinkedIn Outreach Matters

- InMail messaging is often a time-consuming process when done manually.
- Automating LinkedIn outreach increases engagement and responses.
- Enables consistent, personalized communication at scale without human errors.
- Saves time for businesses and recruiters by automating the workflow.
- Great for lead generation, recruitment, and B2B networking.

## Core Features

| Feature | Description |
|---------|-------------|
| Targeted Outreach | Automatically sends InMail to users based on job title, location, or industry. |
| Personalization | Personalizes each message with the target’s name, company, and other dynamic fields. |
| Scheduling | Users can schedule InMail sends at specified intervals, avoiding LinkedIn spam filters. |
| Message Templates | Pre-configured templates allow for easy customization and batch sending. |
| Reporting & Analytics | Tracks message delivery, response rates, and engagement metrics. |
| Multi-Account Support | Supports multiple LinkedIn accounts for diversified outreach campaigns. |
| Proxy Integration | Uses rotating proxies to avoid IP bans and increase the tool's scalability. |
| Error Logging | Detailed logs for every action taken, including failed sends and retries. |
| Re-engagement Automation | Sends follow-up messages to individuals who didn’t respond to the initial InMail. |
| Adaptive Message Frequency | Adjusts message send frequency based on response rates and LinkedIn activity. |
| CAPTCHA Solving | Integrated CAPTCHA bypass for smooth operation during automated actions. |
| Customizable Filters | Allows custom filter criteria for advanced targeting of LinkedIn users. |

---

## How It Works

**Input or Trigger** — Users input target profiles, set filters for outreach, and configure message templates.

**Core Logic** — The bot accesses LinkedIn profiles, sends personalized InMail messages, and logs the results for reporting.

**Output or Action** — Personalized InMail messages are sent, and activity is logged in real-time for review.

**Other Functionalities** — Automatic retry and error handling, including proxy rotation to avoid LinkedIn rate-limiting.

**Safety Controls** — Built-in rate-limiting, randomized delays between sends, and IP rotation to prevent account bans or penalties.

---

## Tech Stack

List core technologies used:

**Language:** Python

**Frameworks:** Selenium, Requests

**Tools:** Appium, BeautifulSoup, Rotating Proxies

**Infrastructure:** Cloud-based servers, Docker, Cron jobs for scheduling

---

## Directory Structure

    linkedin-inmail-bot/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── tasks.py
    │   │   ├── scheduler.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── proxy_manager.py
    │   │       └── config_loader.py
    ├── config/
    │   ├── settings.yaml
    │   ├── credentials.env
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── results.json
    │   └── report.csv
    ├── requirements.txt
    └── README.md

---

## Use Cases

- **Recruiters** use it to send personalized LinkedIn InMail messages, so they can reach more candidates efficiently and reduce manual outreach time.
- **B2B marketers** use it to connect with decision-makers, so they can generate more leads for their sales pipeline.
- **Job seekers** use it to reach out to potential employers, so they can increase their chances of landing interviews and job offers.
- **Sales teams** use it to automate LinkedIn messaging campaigns, so they can scale outreach efforts and track results effortlessly.

---

## FAQs

**Q1: How does the bot handle LinkedIn’s limits on messaging?**

A1: The bot is designed with rate-limiting safeguards. It adjusts the frequency of messages based on LinkedIn's daily sending limits and includes randomized delays between actions.

**Q2: Can the bot work with multiple LinkedIn accounts?**

A2: Yes, the bot supports multiple LinkedIn accounts, allowing businesses and recruiters to scale their outreach efforts without running into account bans.

**Q3: How are errors handled in the bot?**

A3: The bot features automatic retries for failed messages, with detailed logging for each attempt, including reasons for failure. Alerts are sent if a threshold is exceeded.

**Q4: Is CAPTCHA bypass supported?**

A4: Yes, the bot uses a CAPTCHA solving service to bypass LinkedIn's verification process, ensuring uninterrupted operation.

**Q5: How do I ensure privacy when using the bot?**

A5: All sensitive data, like credentials, is securely stored in an encrypted `.env` file, and proxies are rotated to prevent IP bans.

---

## Performance & Reliability Benchmarks

**Execution Speed:** The bot can send up to 200 InMails per hour with typical proxy rotation.

**Success Rate:** 93% successful message deliveries with retries for failed sends.

**Scalability:** Designed to handle 100+ LinkedIn accounts simultaneously by distributing tasks across multiple worker instances.

**Resource Efficiency:** Each worker utilizes 0.5 GB of RAM and 1 CPU core on average, while each LinkedIn account requires ~50 MB of RAM during operations.

**Error Handling:** Automated retries, structured logging for all actions, configurable backoff periods, and real-time alerts via email or Slack.


<p align="center">
<a href="https://cal.com/app-pilot-m8i8oo/30min" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 
  <a href="https://www.youtube.com/@Appilot-app/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
