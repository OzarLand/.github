<div align="center">

# 🏝️ Welcome to OzarLand

**What OpenStack operators learn running it: fixes, deployment choices, experience.**

An early-stage, independent space, open to everyone, whatever tool deployed your cloud.

<p>
  <a href="https://github.com/OzarLand/ozarland"><img src="https://img.shields.io/badge/start-here-f59e0b.svg" alt="Start here"></a>
  <img src="https://img.shields.io/badge/stage-early-orange.svg" alt="Stage: early">
  <a href="https://github.com/OzarLand/ozarland/discussions"><img src="https://img.shields.io/badge/ask-Discussions-8A2BE2.svg" alt="Discussions"></a>
  <img src="https://img.shields.io/badge/license-Apache--2.0-blue.svg" alt="License: Apache-2.0">
</p>

</div>

---

## 🚪 Pick your door

| You are… | Go to |
|---|---|
| 🌱 **New to OpenStack** | [Newcomer path](https://github.com/OzarLand/ozarland/blob/main/newcomers/README.md): five short pages, read in order |
| 🧪 **Want to try OpenStack** | [openstack-quick-lab](https://github.com/OzarLand/openstack-quick-lab): one VM, about one hour, one command to delete it |
| 🔧 **Fixing a problem with a VM** | [VM runbooks](https://github.com/OzarLand/openstack-vm-runbooks#index): find your symptom, follow the steps |
| 🏗️ **Deploying a platform** | [Deployment patterns](https://github.com/OzarLand/kolla-ansible-deployment-patterns#index): how platforms are built with Kolla-Ansible, and what each choice implies |
| 🤖 **Using an AI assistant on call** | [openstack-operator-skills](https://github.com/OzarLand/openstack-operator-skills): Claude skills that apply this knowledge and say how well each procedure was tested |
| 🤝 **Ready to contribute** | [Your first contribution](https://github.com/OzarLand/ozarland/blob/main/newcomers/first-contribution.md): start with ten minutes |

💬 A question? [Start a discussion](https://github.com/OzarLand/ozarland/discussions).

## 🗺️ How the repositories fit together

```mermaid
flowchart TB
    HUB["🏝️ ozarland<br/>start here · rules · Discussions"]
    HUB --> KB
    subgraph KB ["Knowledge and tools"]
        direction LR
        QL["🧪 openstack-quick-lab<br/>disposable lab"] -- "exercises use" --> RB["🔧 openstack-vm-runbooks<br/>symptom-driven runbooks"]
        SK["🤖 openstack-operator-skills<br/>Claude skills"] -- "draws on" --> RB
        SK -- "draws on" --> DP["🏗️ kolla-ansible-deployment-patterns<br/>how platforms are deployed"]
    end
```

## 🔬 Every page says how much it was checked

```mermaid
flowchart LR
    D["📝 draft"] --> L["🧪 lab-verified"] --> V["✅ validated<br/><i>by a human operator<br/>on a real platform</i>"]
    classDef grey fill:#f3f4f6,stroke:#9ca3af,color:#111827
    classDef green fill:#dcfce7,stroke:#16a34a,color:#14532d
    classDef blue fill:#dbeafe,stroke:#2563eb,color:#1e3a8a
    class D grey
    class L green
    class V blue
```

Pages are written and lab-tested with AI agents, and validated only by human operators. Nothing is `validated`
yet: read every page as a well-documented lead, not as a proven procedure.
[Live status](https://github.com/OzarLand/ozarland#-project-status) ·
[How OzarLand is built](https://github.com/OzarLand/ozarland/blob/main/docs/how-ozarland-is-built.md)

## 🙌 How you can help

| | |
|:-:|---|
| ✅ | Run a page on your platform and say what happened |
| 🛠️ | Share a problem you solved |
| ❓ | Ask the question you could not find answered |

<sub>OzarLand is an independent community initiative, not affiliated with or endorsed by the OpenInfra Foundation or
any vendor. Content under the Apache License 2.0.</sub>
