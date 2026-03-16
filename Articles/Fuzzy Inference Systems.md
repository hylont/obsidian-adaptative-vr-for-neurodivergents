---
author: Adnan Mazraeh
year: "2025"
url: https://medium.com/@adnan.mazraeh1993/week-4-fuzzy-inference-systems-fis-ab7758d80800
---

A typical FIS consists of four main components:

## Fuzzification

Converts crisp inputs (real-world values) into fuzzy values.

For example, if the input is the temperature in a room, we might fuzzify the temperature into categories like “cold,” “warm,” and “hot” with values like:
- **Cold**: 0 to 20°C
- **Warm**: 15 to 30°C
- **Hot**: 25 to 40°C

The fuzzification process involves determining the degree to which a crisp value belongs to each category. For instance, a temperature of 18°C might belong to “cold” by 0.3, to “warm” by 0.7, and not belong to “hot” at all.
## Rule Base

A typical if-then rule might look like:

- **If temperature is cold, then fan speed is low**
- **If temperature is warm, then fan speed is medium**
- **If temperature is hot, then fan speed is high**

In FIS, these rules are generally expressed in terms of fuzzy sets and operations (like AND, OR, NOT). The combination of rules creates a system of behavior based on fuzzy logic.
## Inference engine

The inference engine is the component responsible for processing the fuzzy inputs using the rule base and producing fuzzy outputs. It follows the fuzzy reasoning process, which combines the fuzzy input values with the rules in the rule base.

The inference engine works by:

- **Evaluating the rule base**: It checks which rules apply based on the fuzzy inputs.
- **Aggregating the rule outputs**: For each active rule, the output fuzzy sets are calculated.
- **Fuzzy logic operations**: It performs operations (like AND, OR, or Min/Max) to combine the fuzzy outputs from different rules.
## Defuzzification

the process of converting the fuzzy output into a crisp (precise) value, which is the final output of the system. This step is essential to transform fuzzy results into something actionable or usable in real-world applications.