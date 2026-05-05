<!--
SEO Keywords: Kubernetes Consulting Deutschland, Platform Engineering Germany,
On-Premise Kubernetes, OpenShift Kubernetes, Internal Developer Platform,
DevOps Beratung, GitOps, Helm, ArgoCD, Crossplane, Backstage,
IT Beratung Deutschland, Cloud Native, CNCF, Infrastructure as Code,
Secure Platform Engineering, KRITIS, BSI Grundschutz, Regulated Industries
-->

<div align="center">

# Autovia GmbH

## „The Platform Engineering Company"

### Kubernetes | Platform Engineering | GitOps | Cloud Native | Deutschland

**Ihr Spezialist für Kubernetes-Plattformen und Platform Engineering in Deutschland**

[![CNCF Member](https://img.shields.io/badge/CNCF-Member-0086FF?style=flat-square&logo=cncf&logoColor=white)](https://autovia.de)
[![Linux Foundation](https://img.shields.io/badge/Linux%20Foundation-Member-003366?style=flat-square&logo=linux&logoColor=white)](https://autovia.de)

[Website](https://autovia.de) | [Github](https://github.com/autovia) | [info@autovia.ai](mailto:info@autovia.ai) | [LinkedIn](https://www.linkedin.com/company/autovia-gmbh)


---

**Crafting Kubernetes Platforms.**

</div>

---

## Wer wir sind

**Autovia GmbH** ist ein spezialisiertes Engineering-Unternehmen mit Fokus auf **Kubernetes** und **Platform Engineering**. Wir bauen skalierbare, produktionsreife Container-Plattformen und Internal Developer Platforms (IDPs) für Unternehmen in Deutschland.

> **Was uns unterscheidet:** Wir sind 100% Engineers. Wir bauen Plattformen, die wirklich funktionieren: selbstbedienbar, sicher, skalierbar.

| Kennzahl | Wert |
|----------|------|
| **Fokus** | Kubernetes & Platform Engineering |
| **Techie-Quote** | 100% Engineers |
| **Standort** | Deutschland, Bayern, Ingolstadt |
| **Mitgliedschaften** | CNCF, Linux Foundation |
| **Kunden** | Mittelstand bis Enterprise |

---

## Unsere Kernkompetenzen

### Kubernetes Platform Engineering

Wir designen, migrieren und betreiben produktionsreife Kubernetes-Plattformen:

| Service | Beschreibung |
|---------|--------------|
| **Platform Design** | Architektur und Konzeption von Kubernetes-Plattformen |
| **Cluster Setup** | On-Premise, Managed (AKS, EKS, GKE) oder Hybrid |
| **Migration** | Von VMs und Legacy-Systemen zu Containern |
| **Security Hardening** | Pod Security, Network Policies, OPA/Gatekeeper |
| **Networking** | Service Mesh (Istio, Linkerd), Ingress, CNI |
| **Operations** | Managed Services, Monitoring, Day-2-Operations |

#### Kubernetes-Distributionen

- **On-Premise:** Bare-Metal, VMware Tanzu, Red Hat OpenShift
- **Managed Cloud:** AKS (Azure), EKS (AWS), GKE (Google)
- **Edge & Lightweight:** K3s, MicroK8s, Rancher
- **Enterprise:** Red Hat OpenShift, Rancher by SUSE

---

### Internal Developer Platforms (IDP)

Wir bauen Self-Service-Plattformen, die Entwickler schneller und autonomer machen:

```
Backstage       → Developer Portal & Software Catalog
Port            → Internal Developer Portal
Crossplane      → Kubernetes-native Infrastructure Provisioning
Kratix          → Platform as a Product
Humanitec       → Platform Orchestrator
```

**Unsere IDP-Prinzipien:**
- **Self-Service** – Entwickler provisionieren Ressourcen ohne Ops-Tickets
- **Golden Paths** – Standardisierte Workflows für häufige Aufgaben
- **Everything as Code** – Policies, Pipelines, Infrastruktur in Git
- **Inner Source** – Plattform-Teams arbeiten wie Open-Source-Projekte

---

### GitOps & CI/CD

Moderne Deployment-Praktiken für sichere, reproduzierbare Releases:

```yaml
ArgoCD          → GitOps-Deployments für Kubernetes
Flux            → GitOps-Controller für Kubernetes
GitHub Actions  → Cloud-native CI/CD
GitLab CI       → Self-hosted oder SaaS
Tekton          → Cloud-native Pipeline Engine
```

---

### Migration: Legacy CI/CD → Cloud Native

Viele Unternehmen betreiben noch gewachsene Build- und Deployment-Infrastruktur. Wir kennen diese Systeme und migrieren sie schrittweise auf cloud-native Plattformen – ohne Betriebsunterbrechung.

| Legacy | Cloud Native | Was sich verbessert |
|--------|-------------|---------------------|
| **Jenkins** | GitHub Actions / Tekton / ArgoCD | Kein Ops-Overhead, GitOps-fähig, skalierbar |
| **Bamboo** | GitHub Actions / GitLab CI | Managed, weniger Maintenance, bessere Developer Experience |
| **TeamCity** | GitLab CI / Tekton | Self-hosted oder SaaS, Container-native Pipelines |
| **Bitbucket Pipelines** | GitHub Actions / ArgoCD | Native Kubernetes-Integration, GitOps-Workflows |
| **GoCD** | Flux / ArgoCD | Deklarativ, Kubernetes-nativ, Pull-based Deployments |
| **Spinnaker** | ArgoCD + Rollouts | Leichtgewichtiger, Kubernetes-first, einfacher zu betreiben |
| **Nexus / Artifactory** | Harbor / OCI Registries | Kubernetes-native Container Registry, Cosign-Integration |
| **Rundeck** | Kubernetes Jobs / CronJobs | Deklarativ, versioniert, kein separater Scheduler |

**Unser Migrationsprinzip:** Kein Big-Bang-Ansatz. Wir migrieren Pipeline für Pipeline, etablieren Golden Paths auf der neuen Plattform und schaffen Vertrauen im Team, bevor das Legacy-System abgeschaltet wird.

---

### Infrastructure as Code

Automatisierte, versionierte Infrastruktur für volle Reproduzierbarkeit:

```
Crossplane      → Kubernetes-native Infrastructure Provisioning
Pulumi          → IaC mit echten Programmiersprachen (Go, Python)
Ansible         → Configuration Management & Bootstrapping
Helm            → Kubernetes Package Management
Kustomize       → Kubernetes-native Konfiguration
```

---

### Programmiersprachen

Wir entwickeln Platform-Tooling, Kubernetes-Operatoren und Automatisierung in:

| Sprache | Einsatzgebiet |
|---------|---------------|
| **Go** | Kubernetes Operators, Controller, CLI-Tools, Platform APIs |
| **Python** | Automatisierung, Scripting, Infrastructure Tooling, CI/CD-Pipelines |
| **Rust** | Sicherheitskritische Komponenten, performante System-Tools, WebAssembly |
| **TypeScript / JavaScript** | Platform-UIs, Backstage-Plugins, CLI-Tools, Automatisierungs-Skripte |
| **Nix** | Reproduzierbare Build-Umgebungen, Entwickler-Shells, System-Konfiguration |
| **Shell (Bash/POSIX)** | Bootstrapping, Init-Container, CI/CD-Glue, Systemadministration |

---

### Nix & NixOS

Wir nutzen Nix und NixOS für vollständig reproduzierbare Entwicklungs- und Produktionsumgebungen:

| Einsatzgebiet | Beschreibung |
|---------------|--------------|
| **Reproduzierbare Dev-Shells** | `nix develop` stellt identische Toolchains für alle Engineers bereit – keine "works on my machine"-Probleme |
| **NixOS-Systeme** | Deklarative Betriebssystemkonfiguration für Bare-Metal- und VM-Hosts |
| **Nix Flakes** | Versionierte, lockbare Abhängigkeiten für Build-Systeme und Umgebungen |
| **Container-Images mit Nix** | Minimale, reproduzierbare OCI-Images ohne Dockerfile via `pkgs.dockerTools` |
| **CI/CD-Umgebungen** | Deterministisches Build-Caching, identische Builds lokal und in der Pipeline |


---

### Observability & Platform Operations

| Tool | Einsatzgebiet |
|------|---------------|
| **Prometheus** | Metrics Collection & Alerting |
| **Grafana** | Dashboards & Visualization |
| **Loki** | Log Aggregation |
| **Tempo** | Distributed Tracing |
| **OpenTelemetry** | Vendor-neutral Instrumentation |
| **Kiali** | Service Mesh Observability |

---

## Sichere Plattformen in regulierten Umgebungen

Wir bauen und betreiben Kubernetes-Plattformen für Umgebungen mit höchsten Sicherheits- und Compliance-Anforderungen – von kritischer Infrastruktur über Finanzdienstleister bis hin zu öffentlichen Institutionen.

### Sicherheitsarchitektur

| Bereich | Maßnahmen |
|---------|-----------|
| **Supply Chain Security** | SBOM-Generierung, signierten Container-Images (Cosign/Sigstore), Vulnerability Scanning (Trivy, Grype) |
| **Runtime Security** | Falco, Seccomp-Profile, AppArmor, gVisor für Workload-Isolation |
| **Netzwerksicherheit** | Zero-Trust-Networking, Network Policies, mTLS via Service Mesh (Istio) |
| **Secrets Management** | HashiCorp Vault, External Secrets Operator, keine Secrets in Git |
| **Policy Enforcement** | OPA/Gatekeeper, Kyverno – Compliance automatisch durchsetzen |
| **Cluster Hardening** | CIS Kubernetes Benchmark, RBAC-Minimalprinzip, Audit Logging |

### Compliance & Standards

Wir kennen die regulatorischen Anforderungen in Deutschland und Europa:

- **BSI IT-Grundschutz** – Umsetzung von Maßnahmen für Kubernetes-Umgebungen
- **KRITIS** – Hochverfügbare, ausfallsichere Plattformen für kritische Infrastruktur
- **DSGVO / GDPR** – Datensouveränität, On-Premise- und Sovereign-Cloud-Deployments
- **NIS2-Richtlinie** – Sicherheitsanforderungen für wesentliche Einrichtungen
- **ISO 27001** – Informationssicherheits-Management für Plattformumgebungen
- **SOC 2** – Audit-Trails, Zugriffskontrollen, Monitoring

### Air-Gap & Sovereign Deployments

Für Umgebungen ohne Internetzugang oder mit strengen Datensouveränitätsanforderungen:

```
Air-Gap Cluster         → Vollständig isolierte Kubernetes-Umgebungen
Private Container Registry → Harbor, Quay – interne Image-Distribution
Offline-Updates         → Kontrollierte Upgrade-Prozesse ohne externe Abhängigkeiten
Sovereign Cloud         → On-Premise oder dedizierte Cloud-Regionen in Deutschland
```

---

## PKI, Kryptografie & Authentifizierung

Sichere Plattformen erfordern durchgängige Identitäts- und Verschlüsselungsinfrastruktur. Wir konzipieren und betreiben den vollständigen Stack – von der Root CA bis zur Workload-Identität.

### Public Key Infrastructure (PKI)

| Technologie | Einsatzgebiet |
|-------------|---------------|
| **cert-manager** | Automatisierte Zertifikatsverwaltung in Kubernetes (ACME, Vault, selbstsigniert) |
| **HashiCorp Vault PKI** | Interne CA, kurzlebige Zertifikate, automatische Rotation |
| **EJBCA** | Enterprise-PKI für regulierte Umgebungen und Behörden |
| **AWS Private CA / Azure Key Vault** | Managed PKI in Cloud-Umgebungen |
| **cfssl / step-ca** | Leichtgewichtige PKI für interne Microservices |

### TLS / SSL

- End-to-End-TLS in Kubernetes: Ingress → Service → Pod (mTLS via Istio/Linkerd)
- TLS-Policy-Enforcement: Mindestversionen (TLS 1.2/1.3), erlaubte Cipher Suites
- Automatische Zertifikatsrotation ohne Downtime
- Certificate Transparency Monitoring und Ablaufüberwachung

### SSH & Bastion-Infrastruktur

| Technologie | Einsatzgebiet |
|-------------|---------------|
| **HashiCorp Vault SSH** | Kurzlebige, signierte SSH-Zertifikate statt statischer Keys |
| **Teleport** | Zero-Trust-Zugriff auf Kubernetes, SSH und Datenbanken mit Audit-Trail |
| **Boundary** | HashiCorp Boundary für sessionbasierte Infrastrukturzugriffe |
| **OpenSSH Hardening** | Konfigurationshärtung nach BSI- und CIS-Empfehlungen |

### Kerberos & Enterprise-Authentifizierung

| Technologie | Einsatzgebiet |
|-------------|---------------|
| **MIT Kerberos / Heimdal** | KDC-Betrieb und Integration in Linux-Plattformen |
| **Active Directory / FreeIPA** | Kerberos-basierte Identität für On-Premise-Umgebungen |
| **SPIFFE / SPIRE** | Workload-Identität für Kubernetes und heterogene Infrastruktur |
| **OIDC / OAuth 2.0** | Föderierte Authentifizierung, SSO-Integration (Keycloak, Dex) |

### Kryptografie & Secrets Management

```
HashiCorp Vault         → Zentrales Secrets Management, Encryption as a Service
External Secrets Operator → Kubernetes-native Synchronisierung aus Vault / Cloud KMS
SOPS                    → Verschlüsselte Secrets in Git (age, PGP)
Sealed Secrets          → Kubernetes-native verschlüsselte Secrets
AWS KMS / Azure Key Vault / GCP KMS → Cloud-seitige Schlüsselverwaltung
Cosign / Sigstore       → Kryptografisches Signieren von Container-Images
```

---

## Local AI auf Kubernetes

Wir bauen und betreiben enterprise-grade AI-Stacks auf Kubernetes – vollständig On-Premise, DSGVO-konform und produktionsreif. Kein SaaS, keine externen APIs, volle Datensouveränität.

### AI Operator Stack

Wir deployen und betreiben KI-Infrastruktur über Kubernetes-Operatoren und Cloud-native Tooling:

| Komponente | Technologie | Beschreibung |
|------------|-------------|--------------|
| **Model Serving** | vLLM, Ollama, KServe, Triton Inference Server | Hochperformantes LLM-Serving auf Kubernetes |
| **AI Operator** | KubeAI Operator, OpenShift AI | Kubernetes-native Verwaltung von Modellen und Inferenz-Deployments |
| **GPU Scheduling** | NVIDIA GPU Operator, Time-Slicing, MIG | GPU-Ressourcen für Kubernetes-Workloads bereitstellen und teilen |
| **Model Registry** | MLflow, Hugging Face (privat, air-gapped) | Versionierung und Verwaltung von Modellen |
| **Workflow Orchestration** | Kubeflow Pipelines, Argo Workflows | ML-Pipelines und Batch-Inferenz auf Kubernetes |
| **Vector Databases** | Milvus, Weaviate, Qdrant (on Kubernetes) | Semantische Suche und RAG-Backends |
| **Observability** | Prometheus + Grafana GPU Dashboards, DCGM Exporter | GPU-Auslastung, Inferenz-Latenz, Throughput |

### Unterstützte Modell-Familien

```
Llama (Meta)        → General Purpose, Code, Instruct
Mistral / Mixtral   → Effizient, mehrsprachig
Phi (Microsoft)     → Small Language Models für Edge
Qwen / DeepSeek     → Code und Reasoning
Embedding-Modelle   → nomic-embed, BGE, E5 für RAG-Systeme
```

### Enterprise AI Patterns

- **Private RAG** – Retrieval-Augmented Generation auf internen Dokumenten, ohne Cloud-Anbindung
- **Air-Gap Deployments** – Modelle und Abhängigkeiten vollständig offline betreiben
- **Multi-Model Serving** – Mehrere Modelle parallel, dynamisch skalierbar
- **LoRA Fine-Tuning Pipelines** – Modelle auf unternehmensspezifische Daten anpassen
- **DSGVO-konforme Inferenz** – Daten verlassen nie die eigene Infrastruktur

---

## Kubernetes Enterprise-Integration

Kubernetes ist das Betriebssystem moderner Plattformen – aber Enterprise-Umgebungen bringen gewachsene Infrastruktur mit. Wir integrieren Kubernetes nahtlos in bestehende Netzwerk-, Storage- und Compute-Landschaften.

### Storage

| Produkt / Technologie | Integration |
|-----------------------|-------------|
| **NetApp ONTAP** | Astra Trident CSI-Treiber, NFS/iSCSI/NVMe-oF, Snapshot-Klassen |
| **NetApp StorageGRID** | S3-kompatibler Object Store als Persistent Volume Backend |
| **Pure Storage** | Pure Service Orchestrator (PSO) CSI, Block & File |
| **Dell PowerStore / PowerFlex** | CSI-Treiber, dynamisches Provisioning |
| **Ceph / Rook** | Kubernetes-native verteilter Storage via Rook-Operator |
| **Longhorn** | Leichtgewichtiger Cloud-native Block Storage für On-Premise |
| **OpenEBS** | Container-native Storage für stateful Workloads |

### Netzwerk

| Produkt / Technologie | Integration |
|-----------------------|-------------|
| **Citrix NetScaler (ADC)** | NetScaler Ingress Controller, Load Balancing, WAF, SSL-Offloading |
| **F5 BIG-IP** | F5 Container Ingress Services (CIS), IPAM-Integration |
| **Cisco ACI** | ACI CNI-Plugin, Network Policy aus ACI-Policies ableiten |
| **VMware NSX** | NSX Container Plugin (NCP), Mikrosegmentierung |
| **Palo Alto Firewall** | Kubernetes-aware Firewall-Policies via Panorama |
| **MetalLB** | Bare-Metal LoadBalancer für On-Premise-Cluster |
| **Multus CNI** | Multiple Network Interfaces für spezialisierte Workloads (SR-IOV, DPDK) |

### Compute & Virtualisierung

| Produkt / Technologie | Integration |
|-----------------------|-------------|
| **VMware vSphere / Tanzu** | Kubernetes auf vSphere, VM Operator, vSphere CSI |
| **Nutanix** | Nutanix Kubernetes Engine (NKE), CSI, AHV-Integration |
| **OpenStack** | Magnum, Octavia LoadBalancer, Cinder CSI |
| **Bare Metal (IPMI/Redfish)** | Metal³, Cluster API Provider für Bare-Metal-Provisionierung |
| **NVIDIA DGX / HGX** | GPU Operator, DCGM, MIG-Partitionierung für AI-Workloads |

### Automation & Enterprise Tools

| Produkt / Technologie | Integration |
|-----------------------|-------------|
| **Red Hat AAP (Ansible Automation Platform)** | Kubernetes-Operator für AAP, Ansible als Bootstrapping- und Config-Tool |
| **Ansible** | Cluster-Provisionierung, Node-Konfiguration, Day-2-Automatisierung |
| **ServiceNow** | ITSM-Integration via Backstage, automatisierte Change Requests |
| **Dynatrace / Datadog** | Full-Stack Observability, Kubernetes-Autodiscovery, APM |
| **Splunk** | Log-Forwarding aus Kubernetes via Fluentd/Fluent Bit |
| **HashiCorp Vault** | Secrets-Injection in Enterprise-Umgebungen, LDAP/AD-Auth |
| **LDAP / Active Directory** | RBAC-Integration, OIDC-Bridge via Dex oder Keycloak |

---

## Schnellstart-Angebote

| Angebot | Dauer | Ergebnis |
|---------|-------|----------|
| **Kubernetes Platform Review** | 1 Woche | Assessment mit konkreten Handlungsempfehlungen |
| **Platform Engineering Workshop** | 2 Tage | IDP-Strategie und Roadmap |
| **GitOps Enablement** | 2 Wochen | ArgoCD/Flux Setup mit CI/CD-Integration |
| **Kubernetes Migration** | 4–8 Wochen | Produktionsreife Container-Plattform |
| **IDP Kickstart** | 6 Wochen | Backstage-basiertes Developer Portal |



## Kontakt

<div align="center">

| Kanal | Kontakt |
|-------|---------|
| **Website** | [autovia.de](https://autovia.de) |
| **Adresse** | Autovia GmbH, Münchener Str. 79, 85051 Ingolstadt |
| **E-Mail** | [info@autovia.ai](mailto:info@autovia.ai) |
| **GitHub** | [github.com/autovia](https://github.com/autovia) |
| **LinkedIn** | [linkedin.com/company/autovia-gmbh](https://www.linkedin.com/company/autovia-gmbh) |

---

**Autovia GmbH** — „The Platform Engineering Company"

*Wir bauen Kubernetes-Plattformen, die skalieren.*

</div>
