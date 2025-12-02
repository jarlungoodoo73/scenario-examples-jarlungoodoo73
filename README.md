# Killercoda Scenario Examples

A comprehensive collection of example scenarios for [Killercoda](https://killercoda.com/), the interactive learning platform.

## Quick Links

- **Live Examples**: https://killercoda.com/examples
- **Creator Documentation**: https://killercoda.com/creators
- **Course Examples**: https://github.com/killercoda/scenario-examples-courses

## Available Scenarios

### Basic Scenarios

| Scenario | Description | Backend |
|----------|-------------|---------|
| [ubuntu-simple](./ubuntu-simple) | Simple Ubuntu environment | Ubuntu |
| [ubuntu-custom-content](./ubuntu-custom-content) | Custom markdown for all phases | Ubuntu |

### Code & Scripting

| Scenario | Description | Backend |
|----------|-------------|---------|
| [code-actions](./code-actions) | Let users copy or exec code blocks | Ubuntu |
| [code-snippets](./code-snippets) | Include code snippets of various languages | Ubuntu |
| [foreground-background-scripts](./foreground-background-scripts) | Execute code automatically in foreground and background | Ubuntu |
| [foreground-background-scripts-multi-step](./foreground-background-scripts-multi-step) | Multiple steps with foreground and background scripts | Ubuntu |
| [foreground-background-scripts-multi-step-ide](./foreground-background-scripts-multi-step-ide) | Multi-step scripts with IDE interface | Ubuntu |

### Kubernetes

| Scenario | Description | Backend |
|----------|-------------|---------|
| [kubernetes-1node](./kubernetes-1node) | Single node Kubernetes cluster | Kubernetes kubeadm 1-node |
| [kubernetes-2node-multi-step-verification](./kubernetes-2node-multi-step-verification) | Two node cluster with verification | Kubernetes kubeadm 2-nodes |
| [kubernetes-dashboard](./kubernetes-dashboard) | Run and access the Kubernetes Dashboard | Kubernetes kubeadm 1-node |
| [kubernetes-volumes](./kubernetes-volumes) | PV/PVC volumes in Kubernetes | Kubernetes kubeadm 1-node |

### Networking

| Scenario | Description | Backend |
|----------|-------------|---------|
| [network-traffic](./network-traffic) | Access services running inside an environment | Ubuntu |
| [network-traffic-kubernetes](./network-traffic-kubernetes) | Access services in Kubernetes environment | Kubernetes kubeadm 2-nodes |

### IDE & Visual

| Scenario | Description | Backend |
|----------|-------------|---------|
| [theia-ide-visual-editor](./theia-ide-visual-editor) | Theia IDE as default interface | Ubuntu |
| [use-images](./use-images) | Display images in Markdown | Ubuntu |

### Assets & Verification

| Scenario | Description | Backend |
|----------|-------------|---------|
| [upload-assets](./upload-assets) | Upload files as assets to specific locations | Ubuntu |
| [verification](./verification) | Verify user input | Ubuntu |
| [assets](./assets) | Shared assets (logo, etc.) | N/A |

### Learning Paths

| Scenario | Description | Backend |
|----------|-------------|---------|
| [learning-linux](./learning-linux) | Linux learning scenarios with verification | Ubuntu |

## Scenario Structure

Each scenario follows the Killercoda structure:

```
scenario-name/
├── index.json          # Scenario configuration
├── intro.md            # Introduction content
├── step1.md            # Step 1 content
├── step2.md            # Step 2 content (if applicable)
├── finish.md           # Conclusion content
├── background.sh       # Background script (optional)
├── foreground.sh       # Foreground script (optional)
└── verify.sh           # Verification script (optional)
```

## Creating Your Own Scenarios

1. Create a new directory for your scenario
2. Add an `index.json` with your scenario configuration
3. Add markdown files for intro, steps, and finish
4. (Optional) Add scripts for automation and verification

For detailed documentation, visit the [Killercoda Creator Docs](https://killercoda.com/creators).
