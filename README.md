# Azure OpenAI Monitoring Across Subscriptions
This repository contains scripts and templates for monitoring Azure OpenAI resources across multiple subscriptions. By utilizing the metrics and logs available in Azure Monitor, you can track the performance, usage, and health of Azure OpenAI services efficiently.
## Overview
Monitoring Azure OpenAI models across multiple subscriptions is crucial for ensuring optimal performance and cost management. This repository demonstrates how to set up and automate monitoring processes using built-in Azure OpenAI metrics, as well as custom logs and alerts.
The main resources are based on the official documentation from Microsoft: [Azure OpenAI Monitoring](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/monitor-openai?WT.mc_id=Portal-fx#azure-openai-metrics).


## Features
- **Subscription Management**: Automate monitoring across multiple Azure subscriptions.
- **Metrics Collection**: Real-time collection of essential metrics such as token usage, request volume, and response times, Prompt utilization, PTU Utilization.
- **Alerting**: set up alerts for common operational issues like high latency, throttling, and token limits.
- **Dashboard Integration**: Example Azure Monitor workbooks to visualize the performance of OpenAI services across your environment.
- **Customization**: Supports filtering by subscriptions or specific resources for focused analysis.