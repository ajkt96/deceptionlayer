# DECEPTIONLAYER: Deception Infrastructure

Orchestrates honeypots, canary tokens, and fake credentials to detect attackers.

## Features

- Honeypot deployment (SSH, HTTP, RDP)
- - Canary token generation and tracking
  - - Fake credential deployment
    - - Engagement monitoring and alerting
     
      - ## Quick Start
     
      - ```python
        from src.orchestrator import DeceptionOrchestrator

        orch = DeceptionOrchestrator()
        honeypot = orch.deploy_honeypot("honeypot-ssh", "ssh")
        status = orch.get_status()
        ```

        ## License

        MIT License
        
