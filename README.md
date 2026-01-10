🌐 CYPHER-SECURE v8.9 // THE_WIRED_IRELAND
STATUS: IMMUTABLE
LOCATION: IRELAND_NODE
CLEARANCE: RESTRICTED_STUDENT_ACCESS
> "No matter where you are, everyone is always connected. But in the Wired, we keep the gate locked."
> 
👁️‍🗨️ // OVERVIEW
CYPHER-SECURE is a hybrid Neural-Symbolic AI interface designed for the Irish educational sector. It utilizes Mistral Medium for cognitive processing, wrapped in a Hy/Lisp macro-shell that enforces school regulations and hardware-level whitelisting via FleetDM.
The system is designed to be a "Dublin Guardian"—a helpful, educational presence that cannot be modified, subverted, or used to leak PII.
🏗️ // SYSTEM_STACK
 * Neural: Mistral Medium via LangChain.
 * Symbolic: Hy-Macro gates for permission validation.
 * Context: Irish RAG (Retrieval-Augmented Generation) for local cultural nuance.
 * Security: FleetDM (MDM) enforced whitelisting and Geo-fencing.
 * Privacy: 120-Hour Auto-Purge (5-Day Data Volatility).
📂 // DIRECTORY_STRUCTURE
├── .fleet/                 # FleetDM configuration (The Root of Trust)
├── docs/
│   ├── ARCHIVE_SPECS.md    # Log of failed versions & failure states
│   └── MODEL_CARD.md       # Mistral Medium & Irish RAG parameters
├── src/
│   ├── cypher_engine.py    # Dual Persona: [VTUBER_HIPPIE] / [DUBLIN_GUARDIAN]
│   ├── guardrails.py       # PII scrubbing & Adversarial Command Defense
│   └── ledger.py           # Future-proofed Blockchain audit hooks
├── .env.example            # Mistral/Fleet Credential Template
├── LICENSE                 # MIT License (Read-Only Policy)
└── README.md               # You are here.

🔒 // PROTOCOLS
1. The 120-Hour Reaper
This system is volatile. Per security directives, all search history and conversation buffers are shredded every 5 days.
 * TTL = 432,000 seconds.
 * History is non-recoverable. The Wired does not remember the past.
2. MDM Whitelisting
Access is hardware-controlled.
 * Geo-Fence: Operation is restricted to Ireland.
 * Integrity: Any attempt to modify or bipass the src/ directory will trigger a FleetDM lockdown.
 * Read-Only: All users have Read-Only rights to the logic.
3. The Persona Dispatch
The system shifts based on intent detection:
 * Mode A (Hippie): "Hello warriors ready to protect the digital realm—
 * Gen Z slang , 
 * Mode B (Destroyer): "Aup violations will be punished.
⚡ // INITIALIZATION
Requires Fleet Agent to be in COMPLIANT state.
 * Sync Environment:
   cp .env.example .env && nano .env
 * Bind the Logic:
   hy src/cypher_engine.py
 * Validate Guardrails:
   python3 src/guardrails.py --mode=audit
⚠️ // WARNING
The system cannot change itself. The code is static. The memory is fleeting. The security is absolute.
[Cypher] >> Ready to protect the Digital Realm 🌸
