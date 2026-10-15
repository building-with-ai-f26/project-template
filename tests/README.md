# Verification: Tests & Model Evals (`Test.py` — Build 4)

In this studio, proving your product works has two parts:

1. **Deterministic Tests (Red/Green):**
   - Standard unit/integration tests for your application logic, API routes, parsing, permissions, and error handling.
   - When fixing a bug, write a test that **fails first (Red)**, then ship the fix that makes it **pass (Green)**.

2. **Probabilistic Evals (When Your Product Calls a Model):**
   - Whenever your product sends prompts to an LLM, a single happy-path manual test isn't proof.
   - Include a small dataset of representative inputs (including edge cases and messy/adversarial inputs) and a script that grades whether the model's output meets your bar—plus what each run costs.
