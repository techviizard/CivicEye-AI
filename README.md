# CivicEye-AI

                                    User Reports Issue
                       │
                       ▼
             📷 Vision Analysis Agent
        (Analyzes uploaded image)
                       │
                       ▼
          🧠 Issue Intelligence Agent
 (Combines title + description + vision result)
                       │
                       ▼
        🔍 Duplicate Detection Agent
      (Checks similar nearby reports)
                       │
             Duplicate?
            /          \
         Yes            No
         │               │
Suggest support      Save Report
existing report          │
                         ▼
                Firestore Database
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
Community        Resolution Agent    Dashboard
Verification            │
        │               ▼
        └────────► Status Updates
                         │
                         ▼
         📈 Prediction Agent
                         │
                         ▼
         📄 Executive Summary Agent
