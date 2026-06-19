# Lab: Configuring and Managing Microsoft Entra Join

## Objective
Configure Microsoft Entra ID device join settings, perform both standard 
Entra Join and Entra Hybrid Join scenarios for Windows devices, and 
validate successful device registration.

## Scenario
Contoso Corporation needed to configure Entra ID device settings to allow 
users to join devices to Entra ID, with a maximum device limit per user 
and a designated local administrator on all Entra-joined devices. 
Additionally, some Windows devices joined to the on-premises Active 
Directory Domain Services needed seamless access to cloud services, 
requiring Entra Hybrid Join configuration.

## What I Did

### Exercise 1: Configuring Entra Join
- Configured Microsoft Entra ID device join settings in the admin center
- Set a maximum device join limit per user
- Assigned a local administrator role for all Entra-joined devices
- Joined a Windows device (SEA-WS1) to the tenant and verified successful registration
- Disconnected a device from Entra ID and confirmed removal

### Exercise 2: Configuring Entra Hybrid Join
- Re-configured Microsoft Entra Connect to support hybrid join
- Prepared the environment using Windows Administrative Tools on SEA-SVR1
- Tested the hybrid join process on a domain-joined device (SEA-CL2)
- Verified in Microsoft Entra admin center that SEA-CL2 showed 
  "Microsoft Entra hybrid joined" as the Join Type
- Validated successful hybrid identity device registration

## Result
Successfully configured and validated both standard Microsoft Entra Join 
and Microsoft Entra Hybrid Join, enabling secure device registration for 
both cloud-only and on-premises domain-joined Windows devices.

## Skills Demonstrated
- Microsoft Entra ID device join configuration
- Entra Hybrid Join (on-premises AD DS + Entra ID integration)
- Device registration management and verification
- Microsoft Entra Connect re-configuration
- Local administrator role assignment on managed devices
- Microsoft Entra admin center navigation

## Tools Used
- Microsoft Entra Admin Center
- Microsoft Entra Connect
- Windows Administrative Tools
- Active Directory Domain Services (AD DS)

## Screenshots
*(See screenshots folder)*
