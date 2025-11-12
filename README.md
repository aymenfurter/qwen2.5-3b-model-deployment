<div align="center">
	<h1>Qwen Model KAITO Deployment Sample</h1>
	<p><strong>Deploy and benchmark Qwen2.5-3B across AKS and Azure Container Apps with Microsoft tooling.</strong></p>
</div>

---

### Notebook
- `deploy-multi-platform.ipynb` — end-to-end provisioning, deployment, and performance measurements across GPU and CPU targets.

> ℹ️ Update resource names, regions, and deployment flags in the notebook before running the cells.

### Prerequisites
- Azure CLI (latest) with `az aks` and `az containerapp` extensions installed.
- `kubectl` configured for your Azure subscription.
- KAITO operator enabled on the target AKS clusters.

### Run It
1. Clone this repository and open it in VS Code (preferably with the Azure extensions installed).
2. Launch the `deploy-multi-platform.ipynb` notebook with a Python environment that has access to `tiktoken` and plotting libraries.
3. Execute the cells sequentially to create infrastructure, deploy the model, and capture performance metrics.
