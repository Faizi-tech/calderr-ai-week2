# Validation Report

## Objective

The Smart Form Filler validates structured information extracted from natural language using a Pydantic schema.

---

## Validation Rules

- Job title should be available.
- Location should be available.
- Required skills should contain at least one skill.
- Missing values are represented as `None`.
- The system generates clarification questions instead of guessing missing information.

---

## Test Results

| Test Case | Status | Remarks |
|-----------|--------|---------|
| Test Case 1 | ✅ Passed | Complete information extracted successfully. |
| Test Case 2 | ✅ Passed | Missing fields detected correctly. |
| Test Case 3 | ✅ Passed | Structured extraction successful. |
| Test Case 4 | ✅ Passed | Clarification questions generated. |
| Test Case 5 | ✅ Passed | Complete structured output generated. |

---

## Conclusion

The Smart Form Filler successfully extracts structured information, validates required fields, and requests clarification whenever incomplete information is detected.