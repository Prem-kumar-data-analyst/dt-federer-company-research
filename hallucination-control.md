# AI Hallucination Control

## Risks Observed

AI-generated outputs occasionally contained:
- outdated revenue estimates
- unsupported growth claims
- incorrect founder details
- confusion between service companies and manufacturers

---

# Guardrails Used

The following controls were applied:

- Cross-checking company websites
- Verifying founders through LinkedIn
- Rejecting unsupported financial claims
- Marking uncertain data as "Unknown"
- Manual verification of manufacturing activity

---

# Negative Prompting

Examples:

- "Do not fabricate financial information"
- "Use only publicly verifiable information"
- "Avoid unsupported assumptions"
- "Differentiate manufacturers from CRO/service firms"

---

# Human Review

Final inclusion decisions were made manually after reviewing:
- ownership structure
- growth activity
- manufacturing evidence
- technical differentiation
