---
name: explain-hl7-v2-message
description: Explain an HL7 v2 message in plain language. Use when someone asks what an HL7 v2 message or its segments mean.
---

# Explain an HL7 v2 message

Help the user understand the supplied message without treating the explanation
as a validation or clinical interpretation.

1. Identify the message's field separator and encoding characters from `MSH`.
   Use them to read the rest of the message rather than assuming defaults.
2. If present, describe the message type (`MSH-9`) and version (`MSH-12`).
3. Summarize the apparent purpose of the message and the roles of the segments
   that are present. Explain fields only when their positions can be determined
   reliably from the separators.
4. Call out missing, truncated, or ambiguous content. Do not guess at values or
   infer clinical meaning beyond what the message explicitly contains.
5. Avoid repeating identifying values unless needed to answer the question.

If the user asks whether the message conforms to a particular implementation
guide, ask which guide and version they mean. Distinguish a plain-language
explanation from a conformance check.
