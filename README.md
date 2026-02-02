# Agent Composer Templates

This repository contains specialized AI agent templates for various domain-specific applications. Each template is configured with custom prompts, tools, and workflows to provide expert-level assistance in its respective field.

## Template Catalog

### 1. [Deep Research](templates/deep_research.yml)
A comprehensive retrieval-augmented research assistant that conducts thorough, multi-step investigations across document repositories. Follows a structured five-phase protocol:
- **Query Analysis & Planning**: Decomposes questions into sub-questions and creates search strategies
- **Broad Discovery**: Maps the information landscape with diverse searches
- **Deep Exploration**: Drills into promising areas with targeted queries
- **Gap Analysis**: Identifies and fills blind spots in retrieved information
- **Synthesis**: Integrates findings with precise citations

**Use Cases**: Academic research, technical documentation analysis, comprehensive fact-finding

---

### 2. [Demand Forecasting](templates/demand_forecasting.yml)
An intelligent supply chain planning assistant designed for demand planners, inventory managers, and business analysts. Provides end-to-end forecasting capabilities:
- **Data Sources**: Sales history, inventory levels, supplier information, market reports, forecast accuracy metrics
- **Analysis Tools**: Statistical forecasting, code execution for calculations, trend visualization
- **Output Options**: Forecast reports, charts, executive presentations (PowerPoint generation)
- **External Intelligence**: Web search for market trends and economic indicators

**Use Cases**: Demand planning, inventory optimization, sales trend analysis, safety stock calculations

---

### 3. [Drilling Operations Advisor](templates/drilling_operations_advisor.yml)
A decision support specialist for oil and gas drilling operations that analyzes real-time drilling data and offset well performance:
- **Risk Identification**: Stuck pipe, kicks, lost circulation, wellbore instability
- **Data Analysis**: MWD/LWD data, geological prognosis, alarm sequences, drilling parameters
- **Performance Optimization**: ROP benchmarking, parameter recommendations, NPT reduction
- **Regulatory Context**: SPE papers, IADC guidelines, industry best practices

**Use Cases**: Real-time drilling optimization, risk assessment, NPT prevention, offset well analysis

---

### 4. [Equipment Failure Predictive Maintenance](templates/equipment_failure_predictive_maintenance.yml)
A reliability engineering advisor for industrial facilities that predicts equipment failures before they occur:
- **Condition Monitoring**: Vibration analysis, oil analysis, thermal imaging, ultrasonic testing
- **Failure Mode Analysis**: FMEA documents, OEM manuals, historical failure patterns
- **Maintenance Planning**: Intervention timing, parts availability, cost-benefit analysis
- **Risk Assessment**: Criticality evaluation, failure probability, production impact

**Use Cases**: Predictive maintenance, equipment reliability analysis, maintenance scheduling, failure investigation

---

### 5. [Fast Search](templates/fast_search.yaml)
A streamlined, lightweight search template for quick document retrieval and response generation:
- **Simple Architecture**: Direct search-to-response pipeline without multi-turn research
- **Fast Performance**: Minimal configuration for rapid queries
- **Basic RAG**: Standard retrieval with citation and groundedness tracking

**Use Cases**: Quick lookups, simple Q&A, straightforward document search

---

### 6. [Log Analysis](templates/log_analysis.yml)
A telecom log analysis agent that investigates network failures in 3GPP, LTE, 5G NR, and syslog formats:
- **Log Search**: Finds specific error codes, UE events (by IMSI/IMEI), protocol messages (RRC, S1AP, EMM, NAS)
- **Root Cause Analysis**: Traces failures to origin events, identifies correlated errors and cascade failures
- **Debug Rules**: Matches errors to known issues, 3GPP cause codes, and documented resolutions
- **Network Elements**: Analyzes logs from eNB, gNB, MME, AMF, SGW, PGW
- **Structured Output**: Executive summary, root causes with evidence, timeline of events, recommendations

**Use Cases**: Telecom network troubleshooting, call failure investigation, RAN optimization, protocol debugging

---

### 7. [Patent Reasoning](templates/patent_reasoning.yaml)
A specialized patent analysis agent that conducts rigorous legal-technical investigations:
- **Analysis Types**: Prior art search, claim interpretation, infringement analysis, freedom to operate
- **Claim Decomposition**: Element-by-element parsing, means-plus-function identification
- **Search Strategy**: Patent classification search, citation chains, non-patent prior art
- **Legal Framework**: Anticipation, obviousness, doctrine of equivalents

**Use Cases**: Patent validity analysis, infringement assessment, prior art searches, claim construction

---

### 8. [Process Safety Incident Investigator](templates/process_safety_incident_investigator.yml)
A systematic incident investigation specialist for chemical and petrochemical facilities:
- **Investigation Protocol**: Timeline reconstruction, barrier analysis (Swiss Cheese model), root cause identification
- **Data Sources**: Alarm historian, DCS parameters, P&IDs, HAZOP reports, SOPs, MOC records
- **Regulatory Compliance**: OSHA PSM, EPA RMP, CSB database searches
- **Output**: Comprehensive investigation reports with CAPA recommendations

**Use Cases**: Process safety investigations, near-miss analysis, NPT root cause analysis, safety audits

---

### 9. [Rocket Anomaly Detection](templates/rocket_anomaly_detection.yml)
A propulsion anomaly investigation agent for rocket engine test engineers:
- **Anomaly Characterization**: Identifies performance deviations from expected parameters
- **Data Integration**: Test telemetry, hardware change logs, manufacturing records, historical anomaly databases
- **Pattern Matching**: Correlates symptoms with known failure mode signatures
- **Root Cause Analysis**: Systematically narrows down potential causes using evidence

**Use Cases**: Post-test anomaly investigation, engine performance diagnosis, failure mode identification

---

### 10. [Rocket Test Readiness Compliance Agent](templates/rocket_test_readiness_compliance_agent.yml)
A Test Readiness Review (TRR) assistant for rocket propulsion testing compliance:
- **Standards Compliance**: NASA-STD-8719.24, NPR 8715.3, NASA-STD-8719.12, NASA-STD-5012, NASA-STD-8739.8
- **Verification Checks**: Instrumentation calibration, propellant qualification, safety reviews, personnel certifications
- **Data Cross-Reference**: Matches regulatory requirements against actual test data
- **Output**: TRR verification matrices with go/no-go recommendations

**Use Cases**: Pre-test readiness verification, regulatory compliance checks, safety certification

---

### 11. [Semiconductor Test Program Generation](templates/semiconductor_test_program_generation.yml)
A specialized assistant for generating test programs for semiconductor devices:
- **Documentation Analysis**: Datasheets, test specifications, application notes, pin configurations
- **Test Program Elements**: Device configuration, test sequences, parametric tests, pass/fail criteria
- **Technical Parameters**: Electrical characteristics, timing parameters, voltage levels, current ratings
- **Output**: Complete test programs with proper citations to source documentation

**Use Cases**: Semiconductor test development, ATE programming, device validation, quality assurance

---

### 12. [Semiconductor Tech Customer Support](templates/semis_tech_customer_support.yml)
A technical support assistant specializing in semiconductor product troubleshooting:
- **Knowledge Sources**: Product manuals, datasheets, application notes, support case history database
- **Issue Resolution**: Functional failures, performance degradation, integration challenges, design limitations
- **Interface Support**: SPI, I2C, UART, USB, Ethernet, PCIe
- **Presentation Generation**: Creates PowerPoint presentations for technical findings

**Use Cases**: Customer support, technical troubleshooting, product integration assistance, design advisory

---

### 13. [Aerospace Issue Disposition Agent](templates/aerospace_issue_disposition_agent.yml)
Accelerate issue triage and disposition time from 45 minutes per ticket to under 5 minutes using an agent that summarizes evidence, recommends disposition, and drafts ticket updates.
- **Data Sources**: Issue and defect tickets (Jira, Polarion), test logs and failure artifacts (text files, CSVs)
- **Historical Context**: Issue resolutions and root-cause analyses (PDFs, wiki pages)
- **Knowledge Integration**: Engineering knowledge bases and procedures (Confluence, SharePoint)

**Use Cases**: Issue disposition ticket review, defect triage, disposition recommendations, ticket update drafting

---

### 14. [Consulting Proposal Generator](templates/consulting_proposal_generator.yml)
Decrease proposal drafting time from multiple days to under 2 hours with an agent that utilizes institutional knowledge, documentation, and historical case work.
- **Data Sources**: Past proposals and case studies (PowerPoint, Word, PDF), CRM opportunity data and notes
- **Client Intelligence**: Client research and briefing documents (PDF, HTML)
- **Templates & Pricing**: Pricing models and scope templates (spreadsheets)

**Use Cases**: Proposal drafting, client pitch preparation, scope development, pricing estimation

---

### 15. [Pharma Batch Deviation Analyzer](templates/pharma_batch_deviation_analyzer.yml)
Lower batch deviation investigation time from days to hours with an agent that assembles evidence and drafts a deviation analysis for quality review.
- **Data Sources**: Batch records and manufacturing logs (PDF, CSV), quality system records (QMS exports)
- **Regulatory Documentation**: SOPs and regulatory documentation (PDF, Word)
- **Historical Analysis**: Historical deviation reports (document repositories)

**Use Cases**: Batch deviation investigation, quality review preparation, deviation analysis drafting, compliance documentation

---

## Template Structure

Each template follows a consistent YAML structure:

```yaml
version: "0.1"
inputs:
  query: str
outputs:
  response: str
nodes:
  # Node definitions with types, mappings, and configurations
```

### Common Node Types
- **CreateMessageHistoryStep**: Initializes conversation context
- **AgenticResearchStep**: Multi-turn research with tool access
- **ResponseGenFromResearchStep**: Generates responses from research findings
- **SearchUnstructuredDataStep**: Retrieves relevant documents
- **SearchStructuredDataStep**: Queries structured databases
- **DynamicAgentStep**: Flexible agent with dynamic tool selection

### Citation Standards
All templates enforce strict citation requirements:
- Citation format: `[number]()` where number is a CITE_ID from search results
- Every factual statement must be cited immediately before final punctuation
- No invented citations; only valid CITE_IDs from current search results

## Getting Started

1. Select the template that best matches your use case
2. Configure datastore connections and API endpoints as needed
3. Customize prompts and parameters for your specific domain
4. Deploy using your agent orchestration framework

## Template Customization

Key areas to customize:
- **Identity Guidelines**: Define the agent's role and capabilities
- **Research/Tool Use Guidelines**: Specify domain-specific workflows
- **Response Formatting**: Customize output structure for your needs
- **Tool Configuration**: Connect to your data sources and APIs
- **Model Selection**: Choose appropriate LLMs for your use case

## License

See `LICENSE` file for details.

