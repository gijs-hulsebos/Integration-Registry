# Prompts: {{Service_Name}}

## 🎯 Model-Specific Prompting Logic
* **Best Strategy:** {{e.g., Descriptive Narrative / XML Tagging / Chain-of-Thought}}
* **Optimal Length:** {{Short / Medium / Detailed}}
* **Language Support:** {{e.g., English optimized / Multilingual}}

---

## 👤 System Role / Base Instruction
> Use this as the foundation for the service's personality or primary instruction set.

```text
{{Insert_Standard_System_Prompt_Here}}
```
## 🎬 Service-Specific Examples

### Example 1: {{Use_Case_Name}}

**Input / User Prompt:**
{{Insert_Input_Example}}

**Expected Output Style:**
{{Describe_or_insert_expected_result}}

### Example 2: {{Use_Case_Name}}

**Input / User Prompt:**
{{Insert_Input_Example}}

**Expected Output Style:**
{{Describe_or_insert_expected_result}}

---

## 🛠️ Parameters & Settings

| Parameter | Recommended Value | Purpose |
| :--- | :--- | :--- |
| **Temperature** | {{Value}} | {{Control creativity vs. logic}} |
| **Top-P** | {{Value}} | {{Diversity of tokens}} |
| **Frequency Penalty** | {{Value}} | {{Avoid repetition}} |

---

## 💡 Engineering "Cheat Sheet"

* **Keyword Triggers:** {{e.g., "Cinematic", "4k", "Step-by-step", "JSON only"}}
* **Negative Constraints:** {{e.g., "No fluff", "Do not mention you are an AI"}}
* **Formatting Requirements:** {{e.g., "Always use Markdown headers"}}

---

## 🧪 Prompt Validation Checklist

- [ ] Does it follow the specific syntax of {{Service_Name}}?
- [ ] Are the constraints clearly weighted?
- [ ] Is the output format forced (e.g., via "Few-shot" or "System Role")?
