# Project-synapse---context-remediation-workflow
Context-aware security remediation workflow built with Python and Mermaid flowcharts.

<h2>Overview</h2>
Project Synapse is a Python-based security automation workflow that simulates how suspicious API activity can be analyzed and automatically remediated within an enterprise environment.

The workflow was designed around a leaked API key scenario where multiple applications are actively using compromised credentials. The implementation focuses on contextual threat analysis, risk-based remediation, and automated response actions.


<h2>Features</h2>

. Active session retrieval

. IP reputation classification

. Application criticality analysis

. Context-aware risk assessment

. Automated API key rotation

. Malicious session tagging

. Mermaid workflow visualization

<h2>Technologies Used</h2>

. Python

. Visual Studio Code

. Mermaid Flowchart

. Markdown

<h2>Workflow Summary</h2>

The remediation workflow performs the following steps:

. Retrieve active sessions associated with an API key

. Analyze IP reputation and session context

. Determine application criticality levels

. Identify suspicious or high-risk activity

. Trigger automated remediation actions

. Visualize the workflow using Mermaid flowcharts

<h2>Simulated APIs</h2>

<h2>IdentityAPI</h2>

Simulates:

. active session retrieval

. API key rotation

. malicious session tagging

<h2>AssetInventoryAPI</h2>

Handles:

. IP classification

. application criticality mapping

. contextual risk evaluation

<h2>Mermaid Flowchart</h2>

The remediation workflow was visualized using Mermaid syntax inside:

flowchart.md

<h2>The flowchart represents:</h2>

. session analysis

. contextual evaluation

. remediation decision logic

. automated response execution

<h2>Risk Assessment</h2>

The workflow performs contextual risk analysis by combining:

. IP reputation

. application criticality

. remediation conditions

Automated remediation actions are triggered only when suspicious external activity targets high-priority applications.


<h2>Notes</h2>

Sample session IDs, IP addresses, user agents, and application names were manually created to simulate real-world activity inside the testing environment.


<h2>Conclusion</h2>

This workflow demonstrates a simplified security orchestration and automated remediation process commonly used in modern enterprise security operations environments.


<h2>Documentation</h2>

For the complete workflow walkthrough, screenshots, remediation analysis, and flowchart visualization, refer to the PDF report included in this repository.

<h2>File:</h2>

REPORTS.pdf
