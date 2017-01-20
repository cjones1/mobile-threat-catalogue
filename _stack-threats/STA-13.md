---
    layout: threat
    ThreatCategory: Isolated Execution Environments
    ID: STA-13
    Threat: "Reverse engineering of TEE components"
    AttackTactics:
        - "Discovery"
        - "Exploit via Physical Access (no mappable technique)"
    AttackTechniques:
        - "System Information Discovery (more generalized, though, since this is specifically an offline attack)"
    ThreatOrigin: "ARM Security Technology Building a Secure System using TrustZone Technology [^210]"
    ExploitExample:
    CVEExample:
    PossibleCountermeasures:
        "Assume any device that has been under the physical control of an attacker for any timeframe sufficient to have executed this attack has been permanently compromised and should be transitioned to end-of-lifecycle.":
            - Enterprise
---
