---
title: VPN Compatibility
layout: base
---

Overall, the Portmaster is compatible with VPNs. Here we describe what to look out for and known issues with special VPN software.

### Setup

Under normal circumstances, VPNs should work right out of the box. Please [report your experience]({{ site.github_pm_url }}{{ site.github_report_compatibility_url }}) to help others know whether the Portmaster works with a certain VPN client or not. Naturally, when encountering problems we will try to help you get it going.

### Community Reports

| | Status | Issues |
|---|:---|:---:|
| ProtonVPN |  🟢 seen working | [#160](https://github.com/safing/portmaster/issues/160#issuecomment-700528272) |
| RiseupVPN |  🚫 reported broken  | [#284](https://github.com/safing/portmaster/issues/284) |

#### Workaround: OpenVPN

If a VPN Client does not work, you can always work around this by [using OpenVPN instead](https://openvpn.net/community-resources/how-to/). This is a bit more technical but worth a shot if the normal client does not yet work.

### DNS Leak Detection

Please note that pretty much all the DNS leak detection tests by the VPN providers will be a false positive, as the only thing they check is if you are using _their_ DNS servers. Rest assured that your DNS queries are well protected by the Portmaster and there is no need to be concerned.
