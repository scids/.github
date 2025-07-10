# SCIDS – Source-Controlled Infrastructure Declarative Stack  
**Pronounced “Skids”**

---

SCIDS is a Git-native, YAML-first infrastructure platform designed to manage and orchestrate **Docker**, **Kubernetes**, and **KVM virtual machines** side-by-side — all declaratively, with Git as the **single source of truth**.

Whether you're managing a single node or scaling across a hybrid environment, SCIDS brings containers, VMs, and orchestration under a single, auditable control layer.

---

## 🚀 Why SCIDS?

- **Declarative & Git-controlled**  
  All infrastructure is defined in YAML and versioned in Git — enabling full reproducibility and DevOps automation.

- **Unified workload support**  
  Manage Docker Compose stacks, Kubernetes clusters, and KVM virtual machines with passthrough — all in one place.

- **Single-node or multi-node**  
  Designed to work great on a single home server, but built with clustering and horizontal scale in mind.

- **CLI-first, WebUI-optional**  
  Control and inspect everything through CLI or Git. A future web interface will support performance monitoring and node control.

---

## 🧱 Goals

- YAML-based configuration for:
  - Docker & Docker Compose
  - Kubernetes workloads (optionally)
  - Raw KVM VM definitions with passthrough support
- Git as the system’s source of truth
- Horizontal scaling and multi-node coordination
- Minimal required services, fast startup
- Optional GitOps features like per-branch environments

## 📄 License

SCIDS is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)**.

This license ensures that all modifications — including those served over a network — remain open and accessible.

For **commercial use**, enterprise integration, or license exceptions, please contact the maintainers for a commercial license.

---
