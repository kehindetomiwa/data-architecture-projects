# DP-700 Microsoft Fabric Certification — Study Reference Table

A comprehensive reference of Microsoft documentation URLs mapped to every skill listed in the official [DP-700 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-700).

---

## Implement and manage an analytics solution (30–35%)

### A. Configure Microsoft Fabric workspace settings

| Skill | Microsoft Documentation URL |
|---|---|
| Configure Spark workspace settings | https://learn.microsoft.com/en-us/fabric/data-engineering/workspace-admin-settings <br> https://learn.microsoft.com/en-us/fabric/data-engineering/configure-starter-pools <br> https://learn.microsoft.com/en-us/fabric/data-engineering/create-custom-spark-pools <br> https://learn.microsoft.com/en-us/fabric/data-engineering/environment-manage-compute <br> https://learn.microsoft.com/en-us/fabric/data-engineering/create-and-use-environment <br> https://learn.microsoft.com/en-us/fabric/data-engineering/configure-resource-profiles |
| Configure domain workspace settings | https://learn.microsoft.com/en-us/fabric/governance/domains <br> https://learn.microsoft.com/en-us/fabric/admin/service-admin-portal-domain-management-settings <br> https://learn.microsoft.com/en-us/fabric/fundamentals/create-workspaces |
| Configure OneLake workspace settings | https://learn.microsoft.com/en-us/fabric/onelake/onelake-overview <br> https://learn.microsoft.com/en-us/fabric/onelake/onelake-shortcuts <br> https://learn.microsoft.com/en-us/fabric/fundamentals/workspaces |
| Configure data workflow workspace settings | https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-overview <br> https://learn.microsoft.com/en-us/fabric/data-factory/dataflows-gen2-overview |

### B. Implement lifecycle management in Fabric

| Skill | Microsoft Documentation URL |
|---|---|
| Configure version control | https://learn.microsoft.com/en-us/fabric/cicd/cicd-tutorial <br> https://learn.microsoft.com/en-us/fabric/cicd/best-practices-cicd <br> https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-git-deployment-pipelines <br> https://learn.microsoft.com/en-us/fabric/real-time-intelligence/git-deployment-pipelines |
| Implement database projects | https://learn.microsoft.com/en-us/fabric/data-warehouse/source-control <br> https://learn.microsoft.com/en-us/fabric/data-warehouse/development-deployment <br> https://learn.microsoft.com/en-us/fabric/data-warehouse/cross-warehouse-development-database-projects <br> https://learn.microsoft.com/en-us/fabric/database/sql/source-control |
| Create and configure deployment pipelines | https://learn.microsoft.com/en-us/fabric/cicd/deployment-pipelines/intro-to-deployment-pipelines <br> https://learn.microsoft.com/en-us/fabric/data-factory/cicd-pipelines <br> https://learn.microsoft.com/en-us/fabric/data-factory/dataflow-gen2-deployment-pipelines |

### C. Configure security and governance

| Skill | Microsoft Documentation URL |
|---|---|
| Implement workspace-level access controls | https://learn.microsoft.com/en-us/fabric/fundamentals/give-access-workspaces <br> https://learn.microsoft.com/en-us/fabric/security/permission-model |
| Implement item-level access controls | https://learn.microsoft.com/en-us/fabric/data-warehouse/share-warehouse-manage-permissions <br> https://learn.microsoft.com/en-us/fabric/security/permission-model |
| Implement row-level, column-level, object-level, and folder/file-level access controls | https://learn.microsoft.com/en-us/fabric/data-warehouse/security <br> https://learn.microsoft.com/en-us/fabric/data-warehouse/tutorial-row-level-security <br> https://learn.microsoft.com/en-us/fabric/onelake/security/data-access-control-model <br> https://learn.microsoft.com/en-us/fabric/onelake/security/create-manage-roles |
| Implement dynamic data masking | https://learn.microsoft.com/en-us/fabric/data-warehouse/dynamic-data-masking |
| Apply sensitivity labels to items | https://learn.microsoft.com/en-us/fabric/fundamentals/apply-sensitivity-labels <br> https://learn.microsoft.com/en-us/fabric/governance/information-protection <br> https://learn.microsoft.com/en-us/fabric/enterprise/powerbi/service-security-enable-data-sensitivity-labels |
| Endorse items | https://learn.microsoft.com/en-us/fabric/fundamentals/endorsement-promote-certify <br> https://learn.microsoft.com/en-us/fabric/governance/endorsement-overview |
| Implement and use workspace logging | https://learn.microsoft.com/en-us/fabric/fundamentals/workspace-monitoring-overview |
| Configure and implement OneLake security | https://learn.microsoft.com/en-us/fabric/onelake/security/get-started-security <br> https://learn.microsoft.com/en-us/fabric/onelake/security/data-access-control-model |

### D. Orchestrate processes

| Skill | Microsoft Documentation URL |
|---|---|
| Choose between Dataflow Gen2, a pipeline, and a notebook | https://learn.microsoft.com/en-us/fabric/fundamentals/decision-guide-pipeline-dataflow-spark <br> https://learn.microsoft.com/en-us/fabric/fundamentals/prepare-transform-data |
| Design and implement schedules and event-based triggers | https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-runs <br> https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-overview |
| Orchestration patterns with notebooks and pipelines (parameters and dynamic expressions) | https://learn.microsoft.com/en-us/fabric/data-factory/parameters <br> https://learn.microsoft.com/en-us/fabric/data-factory/evaluate-pipeline-expression <br> https://learn.microsoft.com/en-us/fabric/data-engineering/notebookutils/notebookutils-notebook-run |

---

## Ingest and transform data (30–35%)

### A. Design and implement loading patterns

| Skill | Microsoft Documentation URL |
|---|---|
| Design and implement full and incremental data loads | https://learn.microsoft.com/en-us/fabric/data-warehouse/dimensional-modeling-load-tables <br> https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-incremental-copy-data-warehouse-lakehouse |
| Prepare data for loading into a dimensional model | https://learn.microsoft.com/en-us/fabric/data-warehouse/dimensional-modeling-load-tables <br> https://learn.microsoft.com/en-us/fabric/data-factory/slowly-changing-dimension-type-one <br> https://learn.microsoft.com/en-us/fabric/data-factory/slowly-changing-dimension-type-two |
| Design and implement a loading pattern for streaming data | https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-streaming-data <br> https://learn.microsoft.com/en-us/fabric/real-time-intelligence/event-streams/overview |

### B. Ingest and transform batch data

| Skill | Microsoft Documentation URL |
|---|---|
| Choose an appropriate data store | https://learn.microsoft.com/en-us/fabric/fundamentals/decision-guide-pipeline-dataflow-spark <br> https://learn.microsoft.com/en-us/fabric/fundamentals/get-data |
| Choose between dataflows, notebooks, KQL, and T-SQL for data transformation | https://learn.microsoft.com/en-us/fabric/fundamentals/decision-guide-pipeline-dataflow-spark <br> https://learn.microsoft.com/en-us/fabric/fundamentals/prepare-transform-data |
| Create and manage shortcuts to data | https://learn.microsoft.com/en-us/fabric/onelake/onelake-shortcuts |
| Implement mirroring | https://learn.microsoft.com/en-us/fabric/mirroring/overview |
| Ingest data by using pipelines | https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-overview <br> https://learn.microsoft.com/en-us/fabric/data-factory/copy-data-activity |
| Ingest data by using continuous integration from OneLake | https://learn.microsoft.com/en-us/fabric/fundamentals/get-data |
| Transform data by using Power Query (M), PySpark, SQL, and KQL | https://learn.microsoft.com/en-us/fabric/fundamentals/prepare-transform-data <br> https://learn.microsoft.com/en-us/fabric/data-engineering/tutorial-lakehouse-data-preparation |
| Denormalize data; group and aggregate data; handle duplicate, missing, and late-arriving data | https://learn.microsoft.com/en-us/fabric/data-engineering/tutorial-lakehouse-data-preparation <br> https://learn.microsoft.com/en-us/fabric/data-science/data-wrangler-spark |

### C. Ingest and transform streaming data

| Skill | Microsoft Documentation URL |
|---|---|
| Choose an appropriate streaming engine | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/stream-processing <br> https://learn.microsoft.com/en-us/fabric/real-time-intelligence/overview |
| Choose between native storage, mirrored storage, or shortcuts in Real-Time Intelligence | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/onelake-shortcuts |
| Choose between accelerated and non-accelerated shortcuts in Real-Time Intelligence | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/query-acceleration |
| Process data by using eventstreams | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/event-streams/overview |
| Process data by using Spark structured streaming | https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-streaming-data <br> https://learn.microsoft.com/en-us/fabric/data-engineering/notebook-with-event-stream |
| Process data by using KQL | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/overview |
| Create windowing functions | https://learn.microsoft.com/en-us/kusto/query/window-functions |

---

## Monitor and optimize an analytics solution (30–35%)

### A. Monitor Fabric items

| Skill | Microsoft Documentation URL |
|---|---|
| Monitor data ingestion | https://learn.microsoft.com/en-us/fabric/fundamentals/workspace-monitoring-overview <br> https://learn.microsoft.com/en-us/fabric/admin/monitoring-hub |
| Monitor data transformation | https://learn.microsoft.com/en-us/fabric/fundamentals/workspace-monitoring-overview |
| Monitor semantic model refresh | https://learn.microsoft.com/en-us/fabric/fundamentals/workspace-monitoring-overview |
| Configure alerts | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/data-activator/activator-introduction |

### B. Identify and resolve errors

| Skill | Microsoft Documentation URL |
|---|---|
| Identify and resolve pipeline errors | https://learn.microsoft.com/en-us/fabric/data-factory/monitor-pipeline-runs |
| Identify and resolve dataflow errors | https://learn.microsoft.com/en-us/fabric/data-factory/monitoring-dataflow-gen2 |
| Identify and resolve notebook errors | https://learn.microsoft.com/en-us/fabric/data-engineering/spark-job-diagnostic-summary |
| Identify and resolve eventhouse errors | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/manage-data-policies |
| Identify and resolve eventstream errors | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/event-streams/monitor |
| Identify and resolve T-SQL errors | https://learn.microsoft.com/en-us/fabric/data-warehouse/query-insights |
| Identify and resolve Shortcut errors | https://learn.microsoft.com/en-us/fabric/onelake/onelake-shortcuts |

### C. Optimize performance

| Skill | Microsoft Documentation URL |
|---|---|
| Optimize a lakehouse table | https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-table-maintenance <br> https://learn.microsoft.com/en-us/fabric/data-engineering/delta-optimization-and-v-order |
| Optimize a pipeline | https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-performance-overview |
| Optimize a data warehouse | https://learn.microsoft.com/en-us/fabric/data-warehouse/guidelines-warehouse-performance <br> https://learn.microsoft.com/en-us/fabric/data-warehouse/statistics |
| Optimize eventstreams and eventhouses | https://learn.microsoft.com/en-us/fabric/real-time-intelligence/manage-data-policies |
| Optimize Spark performance | https://learn.microsoft.com/en-us/fabric/data-engineering/spark-compute |
| Optimize query performance | https://learn.microsoft.com/en-us/fabric/data-warehouse/query-insights |

---

## Additional Study Resources

- **Official study guide**: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-700
- **Certification landing page**: https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/
- **MS Learn learning paths**: https://learn.microsoft.com/en-us/credentials/certifications/exams/dp-700#two-ways-to-prepare
- **Hands-on labs (GitHub)**: https://microsoftlearning.github.io/mslearn-fabric/
- **Microsoft Fabric documentation home**: https://learn.microsoft.com/en-us/fabric/
- **Data engineering overview**: https://learn.microsoft.com/en-us/fabric/data-engineering/data-engineering-overview
- **Microsoft Fabric blog**: https://blog.fabric.microsoft.com/

---

## Preparation Tips

The three exam domains are weighted roughly equally (30–35% each), so balance your study time across all three. The exam is scenario-heavy — expect a case study of around 10 questions — so hands-on practice in a Fabric trial tenant matters more than reading alone. Build an actual lakehouse, pipeline, eventstream, and deployment pipeline end-to-end. Be comfortable with SQL, PySpark, and KQL syntax, especially KQL `summarize` and windowing functions plus PySpark DataFrame operations. The "choose between X and Y" questions (Dataflow vs pipeline vs notebook, shortcut vs mirroring, eventstream vs Spark structured streaming) are heavily tested — the decision-guide pages are essential reading.
