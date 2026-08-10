# Divverse Labs Community n8n Workflow Library

## Built by the community. Shared with the community.

At Divverse Labs, we believe practical knowledge becomes more valuable when it is shared.

Members of the Divverse Community Labs have built n8n workflows for real business needs—from lead generation and outreach to content creation, research, customer support, reporting, document management, and AI-powered operations.

This repository is our way of giving back. We are gradually open-sourcing the n8n workflows, AI agents, experiments, templates, and automation systems created across Divverse Community Labs so other builders can learn from them, improve them, and use them as starting points.

## What you will find here

This library will grow to include workflows built across the Divverse Community Labs ecosystem, covering:

- AI agents and assistants
- Lead generation and enrichment
- LinkedIn and outreach automation
- Email and communication management
- Sales and GTM operations
- Customer support automation
- Content creation and distribution
- Research and competitor monitoring
- Document and knowledge management
- Meeting and task management
- Data collection and reporting
- Voice, image, audio, and video automation
- Personal productivity
- Experimental automation concepts

The first release contains **79 sanitized workflows** from an anonymized community contributor. More contributor collections and Lab projects will be added as they are reviewed and prepared for public use.

## Repository structure

Each workflow is stored as an individual, clearly named JSON file. The original functional folder structure is preserved under:

`workflows/contributor-01/`

Contributor identities are intentionally anonymized for privacy.

## Using a workflow

1. Download the workflow JSON file.
2. Open your n8n workspace.
3. Create a new workflow.
4. Select **Import from file**.
5. Choose the downloaded JSON file.
6. Reconnect the required credentials.
7. Replace every `REDACTED` placeholder with your own securely stored value.
8. Review the nodes and configuration.
9. Test the workflow before publishing it.

These workflows are learning resources and starting points. Some require changes for your tools, accounts, data structure, n8n version, or business process.

## Security and sanitization

Every workflow is reviewed and sanitized before publication. The process includes:

- Removing n8n credential bindings
- Removing credential IDs and names
- Removing webhook IDs
- Replacing literal webhook paths
- Redacting API keys and access tokens
- Redacting passwords and authorization headers
- Redacting private keys and signing secrets
- Redacting service-specific webhook tokens
- Anonymizing contributor identities
- Scanning files for recognizable secret formats

You must reconnect your own credentials after importing a workflow. Never place passwords, tokens, or API keys directly inside workflow nodes. Use n8n credentials, environment variables, or a secure secrets-management system.

## Important notice

Before using any workflow in production:

- Review every node
- Confirm what data it collects and sends
- Replace all placeholders
- Connect only trusted credentials
- Verify external API endpoints
- Check privacy and data-protection requirements
- Test with non-sensitive data
- Add appropriate error handling and monitoring

Divverse Labs is not responsible for costs, data loss, account restrictions, or other outcomes resulting from unreviewed or incorrectly configured workflows.

## Workflow index

### General workflows

- [Lead gen with googleapi](workflows/contributor-01/lead-gen-with-googleapi.json)
- [Contributor Workflow](workflows/contributor-01/contributor-workflow.json)
- [My workflow 57](workflows/contributor-01/my-workflow-57.json)
- [seven sms test](workflows/contributor-01/seven-sms-test.json)
- [Phantom Webhook](workflows/contributor-01/phantom-webhook.json)
- [Slack and Whatsapp Email Alert](workflows/contributor-01/slack-and-whatsapp-email-alert.json)
- [AI_Blog_to_Podcast_Generator](workflows/contributor-01/ai-blog-to-podcast-generator.json)
- [My workflow 52](workflows/contributor-01/my-workflow-52.json)
- [Looping and Batching demo](workflows/contributor-01/looping-and-batching-demo.json)
- [JD Automation](workflows/contributor-01/jd-automation.json)
- [GTM Campaign Email Inbox Manager](workflows/contributor-01/gtm-campaign-email-inbox-manager.json)
- [Phantombuster](workflows/contributor-01/phantombuster.json)
- [US Restaurant Scraper 2](workflows/contributor-01/us-restaurant-scraper-2.json)
- [US Restaurant Scraper](workflows/contributor-01/us-restaurant-scraper.json)
- [WhatsApp and Slack Alert](workflows/contributor-01/whatsapp-and-slack-alert.json)
- [Blog to podcast generator copy](workflows/contributor-01/blog-to-podcast-generator-copy.json)
- [My workflow 59](workflows/contributor-01/my-workflow-59.json)
- [Automated Newsletter Research team](workflows/contributor-01/automated-newsletter-research-team.json)
- [Contributor 01's Image generation workflow](workflows/contributor-01/contributor-01s-image-generation-workflow.json)
- [My workflow 51](workflows/contributor-01/my-workflow-51.json)
- [My workflow 62](workflows/contributor-01/my-workflow-62.json)

### AI Video Pipeline - Austin Regulations

- [Austin Regulation](workflows/contributor-01/ai-video-pipeline-austin-regulations/austin-regulation.json)

### Loubby's Post Extractor

- [Send Linkedin Connection and message](workflows/contributor-01/loubbys-post-extractor/send-linkedin-connection-and-message.json)
- [Trigger Phantombuster](workflows/contributor-01/loubbys-post-extractor/trigger-phantombuster.json)
- [Send Linkedin Connection and message (Airtable)](workflows/contributor-01/loubbys-post-extractor/send-linkedin-connection-and-message-airtable.json)
- [Receive Post Payload & log to GSheets](workflows/contributor-01/loubbys-post-extractor/receive-post-payload-and-log-to-gsheets.json)

### Subscription and Expenses Reminder Agent

- [Upload invoice/receipts](workflows/contributor-01/subscription-and-expenses-reminder-agent/upload-invoice-receipts.json)
- [WhatsApp ChatBot](workflows/contributor-01/subscription-and-expenses-reminder-agent/whatsapp-chatbot.json)
- [Telegram Chatbot](workflows/contributor-01/subscription-and-expenses-reminder-agent/telegram-chatbot.json)
- [My workflow 82](workflows/contributor-01/subscription-and-expenses-reminder-agent/my-workflow-82.json)
- [Reminders](workflows/contributor-01/subscription-and-expenses-reminder-agent/reminders.json)

### AI-Powered Competitor Analysis (Chat)

_No workflows in this folder._

### AI-Powered Competitor Analysis (Weekly)

- [Monitor competitor product updates and feature releases](workflows/contributor-01/ai-powered-competitor-analysis-weekly/monitor-competitor-product-updates-and-feature-releases.json)
- [Customer Sentiment Monitoring](workflows/contributor-01/ai-powered-competitor-analysis-weekly/customer-sentiment-monitoring.json)
- [Competitor Pricing Monitoring](workflows/contributor-01/ai-powered-competitor-analysis-weekly/competitor-pricing-monitoring.json)
- [Scrape competitor job postings](workflows/contributor-01/ai-powered-competitor-analysis-weekly/scrape-competitor-job-postings.json)
- [Send Email Update](workflows/contributor-01/ai-powered-competitor-analysis-weekly/send-email-update.json)
- [[TEMPLATE] The Ultimate Free AI-Powered Researcher with Tavily Web Search & Extract](workflows/contributor-01/ai-powered-competitor-analysis-weekly/template-the-ultimate-free-ai-powered-researcher-with-tavily-web-search-and-extract.json)

### AI-Powered Outreach Automation

- [Slack Alert for LinkedIn Replies](workflows/contributor-01/ai-powered-outreach-automation/slack-alert-for-linkedin-replies.json)
- [Generate Email, Linkedin and WhatsApp Dms](workflows/contributor-01/ai-powered-outreach-automation/generate-email-linkedin-and-whatsapp-dms.json)
- [Slack Alert for WhatsApp Replies](workflows/contributor-01/ai-powered-outreach-automation/slack-alert-for-whatsapp-replies.json)
- [Follow-Up Email](workflows/contributor-01/ai-powered-outreach-automation/follow-up-email.json)
- [Monitoring Email Replies](workflows/contributor-01/ai-powered-outreach-automation/monitoring-email-replies.json)

### GTM Inbox Manager

- [KB Preprocessing into Vector Store](workflows/contributor-01/gtm-inbox-manager/kb-preprocessing-into-vector-store.json)

### Lead Gen with Google API

- [Generate Email](workflows/contributor-01/lead-gen-with-google-api/generate-email.json)

### Airtop and Linkedin Automation

- [Scrape Attendees (with pagination)](workflows/contributor-01/airtop-and-linkedin-automation/scrape-attendees-with-pagination.json)
- [Watch for Replies and respond](workflows/contributor-01/airtop-and-linkedin-automation/watch-for-replies-and-respond.json)
- [Log Attendees to GSheets & Send Connections](workflows/contributor-01/airtop-and-linkedin-automation/log-attendees-to-gsheets-and-send-connections.json)
- [Fetch All LinkedIn Connections](workflows/contributor-01/airtop-and-linkedin-automation/fetch-all-linkedin-connections.json)
- [Fetch LinkedIn Messages](workflows/contributor-01/airtop-and-linkedin-automation/fetch-linkedin-messages.json)
- [Trigger upon New Connection and send 1st dm](workflows/contributor-01/airtop-and-linkedin-automation/trigger-upon-new-connection-and-send-1st-dm.json)
- [LinkedIn DM Sent](workflows/contributor-01/airtop-and-linkedin-automation/linkedin-dm-sent.json)
- [My workflow 76](workflows/contributor-01/airtop-and-linkedin-automation/my-workflow-76.json)
- [Scrape Events](workflows/contributor-01/airtop-and-linkedin-automation/scrape-events.json)
- [Phantom](workflows/contributor-01/airtop-and-linkedin-automation/phantom.json)

### Communication & Email Management

- [Monitor and flag priority emails](workflows/contributor-01/communication-and-email-management/monitor-and-flag-priority-emails.json)
- [Slack Reminder for Email tasks](workflows/contributor-01/communication-and-email-management/slack-reminder-for-email-tasks.json)
- [Send Meeting Tasks to ClickUp](workflows/contributor-01/communication-and-email-management/send-meeting-tasks-to-clickup.json)
- [Send Email Tasks to ClickUp](workflows/contributor-01/communication-and-email-management/send-email-tasks-to-clickup.json)
- [Slack Reminder for Meeting tasks](workflows/contributor-01/communication-and-email-management/slack-reminder-for-meeting-tasks.json)

### Documentation & Knowledge Management

_No workflows in this folder._

### EVA

- [EVA's Daily Schedule Automation](workflows/contributor-01/eva/evas-daily-schedule-automation.json)
- [EVA Meeting Scheduling Assistant](workflows/contributor-01/eva/eva-meeting-scheduling-assistant.json)
- [Monitor Daily changes](workflows/contributor-01/eva/monitor-daily-changes.json)
- [Slack Meeting Scheduling Assistant](workflows/contributor-01/eva/slack-meeting-scheduling-assistant.json)
- [Prioritize Daily Tasks](workflows/contributor-01/eva/prioritize-daily-tasks.json)
- [Flight Search](workflows/contributor-01/eva/flight-search.json)
- [Manual calendar update request](workflows/contributor-01/eva/manual-calendar-update-request.json)
- [Flight Search (SerpAPI)](workflows/contributor-01/eva/flight-search-serpapi.json)
- [Hotel Search](workflows/contributor-01/eva/hotel-search.json)
- [Personal Errands](workflows/contributor-01/eva/personal-errands.json)
- [EVA's Outbound Caller](workflows/contributor-01/eva/evas-outbound-caller.json)

### Documentation & Knowledge Management / Maintain centralized meeting summaries and decision logs

- [Slide deck generation](workflows/contributor-01/documentation-and-knowledge-management/maintain-centralized-meeting-summaries-and-decision-logs/slide-deck-generation.json)
- [Meeting Notes Processing (Post-Meeting)](workflows/contributor-01/documentation-and-knowledge-management/maintain-centralized-meeting-summaries-and-decision-logs/meeting-notes-processing-post-meeting.json)

### Documentation & Knowledge Management / Create, update, and organize strategic documents

- [Line chart gen sub-workflow](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/line-chart-gen-sub-workflow.json)
- [Create, update, and organize strategic documents](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/create-update-and-organize-strategic-documents.json)
- [Polar Chart gen sub-workflow](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/polar-chart-gen-sub-workflow.json)
- [KB Preprocessing](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/kb-preprocessing.json)
- [Pie chart gen sub-workflow](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/pie-chart-gen-sub-workflow.json)
- [Bar Chart gen sub-workflow](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/bar-chart-gen-sub-workflow.json)
- [Doughnut chart gen sub-workflow](workflows/contributor-01/documentation-and-knowledge-management/create-update-and-organize-strategic-documents/doughnut-chart-gen-sub-workflow.json)

## Contributing

Community members can contribute by submitting workflows, improving existing automations, fixing outdated nodes, adding documentation, reporting security concerns, and sharing reusable variations.

Submitted workflows must not contain credentials, API keys, personal information, private business data, or confidential client information.

## Our goal

Our goal is to build a practical, community-powered n8n library that helps people move beyond tutorials and learn from systems built around real problems.

This is more than a collection of JSON files. It is a growing record of what the Divverse Community is learning, building, testing, and sharing with the world.

## About Divverse Labs

Divverse Labs is a practical learning and innovation community where people develop skills by building real automation, AI, and technology solutions.

We learn by building.

We grow by sharing.

And through this repository, we are giving what we have built back to the community.
