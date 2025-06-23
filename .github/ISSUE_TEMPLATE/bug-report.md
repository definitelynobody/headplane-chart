---
name: 🐛 Bug Report
about: Report a bug in the Headplane Helm Chart
title: '[BUG] '
labels: ['bug', 'needs-triage']
assignees: ''
---

## 🐛 What's the bug?

<!-- Brief description -->

## 🔍 Expected vs Actual

**Expected:** 
**Actual:** 

## 📄 Your values.yaml

```yaml
# Your values.yaml (redact sensitive data)
```

## 🖥️ Environment

- **K8s:** `kubectl version --short`
- **Helm:** `helm version`

## 📝 Logs

```bash
# Relevant logs here
```

## 🔒 Security

**Removed:** API keys, passwords, personal domains

## 🔧 Additional Information

### Events
```bash
kubectl get events -n <namespace> --sort-by='.lastTimestamp'
```

### Describe Resources
```bash
kubectl describe pod <headplane-pod-name> -n <namespace>
kubectl describe pod <headscale-pod-name> -n <namespace>
```

## ✅ Checklist

Before submitting this issue, please ensure you have:

- [ ] ✅ Provided your complete `values.yaml` (with sensitive data redacted)
- [ ] ✅ Included all relevant logs
- [ ] ✅ Checked that the issue is not already reported
- [ ] ✅ Verified your Kubernetes and Helm versions
- [ ] ✅ Confirmed the issue occurs with the latest chart version
- [ ] ✅ Tested with minimal configuration if possible

## 📞 Additional Help

- Checking the [Headplane documentation](https://github.com/tale/headplane)
- Checking the [Headscale documentation](https://github.com/juanfont/headscale)
- Reviewing existing issues for similar problems

---

**Thank you for helping improve the Headplane Helm Chart! 🚀** 