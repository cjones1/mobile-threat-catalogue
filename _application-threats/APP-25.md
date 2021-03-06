---
    layout: threat
    ThreatCategory: "Malicious or privacy-invasive application"
    ID: APP-25
    Threat: "Taking advantage of already rooted/jailbroken device\'s degraded security state to perform malicious action or obtain a persistent presence"
    ThreatOrigin:
    ExploitExample:
        - "How to clean up the Duh iPhone worm [^101]"
    CVEExample:
    PossibleCountermeasures:
        "Deploy MAM or MDM solutions with policies that prohibit the side-loading of apps, which may bypass security checks on the app.":
            - Enterprise
        "Deploy MAM or MDM solutions with policies that prohibit the installation of apps from 3rd party (unofficial) app stores.":
            - Enterprise
        "For the lowest risk tolerance, deploy MDM or containerization solutions with policies that can detect and block access to enterprise resources by rooted/jail-broken devices.":
            - Enterprise
        "Use Android Verify Apps feature to identify harmful apps.":
            - Mobile Device User
        "Use application threat intelligence data to detect potential abuse of rooted/jail-broken BYOD devices":
            - Enterprise
        "To avoid launching applications that handle sensitive information on a rooted/jail-broken device, perform device integrity checking, such as using Android SafetyNet, Samsung Knox hardware-backed remote attestation, or other applicable remote attestation technologies device integrity attestation API": 
            - Mobile App Developer
---
