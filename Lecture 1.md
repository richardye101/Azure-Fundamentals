# Weighting of topics

| **AZ-900 Domain Area**                   | **Weight** |
| ---------------------------------------- | ---------- |
| Describe cloud concepts                  | 25-30%     |
| Describe Azure architecture and services | 35-40%     |
| Describe Azure management and governance | 30-35%     |

Your service model will determine responsibility for things like:

- Operating systems
- Network controls
- Applications
- Identity and infrastructure

Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework.

## Management:

### OF the cloud

Management of the cloud speaks to managing your cloud resources. In the cloud, you can:

- Automatically scale resource deployment based on need.
- Deploy resources based on a preconfigured template, removing the need for manual configuration.
- Monitor the health of resources and automatically replace failing resources.
- Receive automatic alerts based on configured metrics, so you’re aware of performance in real time.

### IN the cloud

Management in the cloud speaks to how you’re able to manage your cloud environment and resources. You can manage these:

- Through a web portal.
- Using a command line interface.
- Using APIs.
- Using PowerShell.

![Diagram showing the responsibilities of the shared responsibility model.](https://learn.microsoft.com/en-ca/training/wwl-azure/describe-cloud-service-types/media/shared-responsibility-b3829bfe.svg)

## Billing

Depending on your needs, you can set up multiple invoices within the same billing account. To do this, create additional billing profiles. Each billing profile has its own monthly invoice and payment method.

![Diagram showing overview of billing structure, with billing account at the top, down to several Azure subscriptions.](https://learn.microsoft.com/en-us/training/modules/create-an-azure-account/media/4-billing-structure-overview.png)

## Azure Support Plans

|                             | Developer               | Standard                           | Professional Direct                                   |
| --------------------------- | ----------------------- | ---------------------------------- | ----------------------------------------------------- |
| Best for                    | Non-critical workloads  | Production workloads               | Business-critical workloads                           |
| Reactive technical support  | 1 business day response | 1-hour response for critical cases | 1-hour response + priority tracking of critical cases |
| Proactive technical support | Not applicable          | Not applicable                     | Access to a pool of technical experts                 |

## Physical Infrastructure

The physical infrastructure for Azure starts with datacenters. Conceptually, the datacenters are the same as large corporate datacenters. They’re facilities with resources arranged in racks, with dedicated power, cooling, and networking infrastructure.

Datacenters are grouped into Azure Regions or Azure Availability Zones that are designed to help you achieve resiliency and reliability for your business-critical workloads.