# Agent – Pre-built Copilot Cowork Investment Assessment Agent

## Overview

This is a pre-built declarative agent packaged as a zip file. An admin can import it into Microsoft 365 and make it available to all users in the organisation.

The agent zip file is included in this folder: **`Cowork Investment Advisor.zip`**

## Import & Deployment Instructions

### Prerequisites

- Microsoft 365 admin access (Global Admin or Teams Admin role)
- Microsoft 365 Copilot licences assigned to target users
- Access to the Microsoft 365 Admin Centre

### Steps

1. **Download** the file `Cowork Investment Advisor.zip` from this folder.

2. **Go to** the [Microsoft 365 Admin Centre](https://admin.microsoft.com) and select **Agents** from the left-hand menu.

3. **Click** "Upload custom agent".

4. **Choose** the `Cowork Investment Advisor.zip` file. The platform will validate the contents.

5. **Verify agent details** — review the agent's name, icon, and which products it will work with, then click **Next**.

6. **Select audience** — assign the agent to specific users, groups, or the entire organisation, then click **Next**.

7. **Review permissions and capabilities** — confirm what the agent can access and do, then click **Next**.

8. **Finalise** — click "Finish deployment" to publish the agent. It is now part of your organisation's agent inventory.

### Post-Deployment

- It may take up to 24 hours for the agent to appear for all assigned users.
- Users can access the agent from the Copilot agent picker in Microsoft 365 Copilot Chat.
- The agent will appear as "Cowork Investment Advisor" in the agent list.

## What the Agent Does

This agent performs a Copilot Cowork Investment Assessment — it identifies workflows suitable for Copilot Cowork automation, assesses complexity, calculates credit consumption and ROI, and provides executive-level recommendations. See [Prompt.MD](../Prompt/Prompt.MD) for the full assessment methodology.
