# DOMAIN-ONLY Filter Lists
**Last Updated:** 2018-02-07 01:51:00

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [EasyList](#easylist-domains-only) (Domains-only)
  - [EasyPrivacy](#easyprivacy-domains-only) (Domains-only)
  - [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) (Domains-only)
  - [NoCoin Filter List](#nocoin-filter-list-domains-only) (Domains-only)
- [Reporting Conversion Issues](#reporting-conversion-issues)

&nbsp;

# Details:
These are "DOMAIN-ONLY" **converted** versions of various popular original filter / blocking lists.
They have been modified from their original versions by scripts at: https://github.com/justdomains/ci

The scripts output **only** the full-domain-blocking entries from the original lists, while attempting to filter any domains that conflict with an exception rule on the original list.

**Because these are automated, converted _subsets_ of the original lists, please do not report omissions from these converted files to the list originator.**

&nbsp;

# Usage:
These converted files can be used with various DNS and domain-blocking tools:

## Using with [Pi-Hole](https://pi-hole.net/):
1. Copy the link to the Pi-Hole format for the desired list (from the appropriate table below).
2. [Add the URL to your Pi-Hole's block lists (**Settings** > **Pi-Hole's Block Lists**).](https://github.com/pi-hole/pi-hole/wiki/Customising-Sources-for-Ad-Lists)

## Using with other tools:
The converted lists are provided in a "Raw Domain List" format that contains only domains, one per line. Many other tools / scripts can ingest this format to add them to your blocklist.

&nbsp;

# The Lists:

| Converted List | Domains | Raw Domain List Link | Last Updated |
:- | - | - | - |
| [EasyList](#easylist-domains-only) | 10524 | [easylist-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/easylist-justdomains.txt) | 07 Feb 2018 00:24 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | 5447 | [easyprivacy-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/easyprivacy-justdomains.txt) | 07 Feb 2018 01:47 UTC |
| [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) | 17319 | [adguarddns-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/adguarddns-justdomains.txt) | 2018-02-06 10:00:43 |
| [NoCoin Filter List](#nocoin-filter-list-domains-only) | 124 | [nocoin-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/nocoin-justdomains.txt) | 04 Feb 2018 |

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/easylist-justdomains.txt) |
| Pi-Hole | [easylist-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/easylist-justdomains.txt) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 201802070024
- Last Modified: 07 Feb 2018 00:24 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 65802
Comment Lines: 379
Empty Lines: 0
Non-Domain-only Rules Excluded: 53357
Domain-only Rules Excluded (unsupported options): 1274
Domain-only Rules Excluded (exception conflict): 268
Domain-only Rules Output: 10524
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/easyprivacy-justdomains.txt) |
| Pi-Hole | [easyprivacy-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/easyprivacy-justdomains.txt) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 201802070147
- Last Modified: 07 Feb 2018 01:47 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 14152
Comment Lines: 183
Empty Lines: 0
Non-Domain-only Rules Excluded: 8248
Domain-only Rules Excluded (unsupported options): 125
Domain-only Rules Excluded (exception conflict): 149
Domain-only Rules Output: 5447
```

&nbsp;

## AdGuard Simplified Domain Names Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/adguarddns-justdomains.txt) |
| Pi-Hole | [adguarddns-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/adguarddns-justdomains.txt) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: Simplified domain names filter
- Version: 1.0.3.55
- Last Modified: 2018-02-06 10:00:43
- Homepage: [https://github.com/AdguardTeam/AdguardDNS](https://github.com/AdguardTeam/AdguardDNS)

**Conversion Details:**
```
Total Lines Processed: 18148
Comment Lines: 139
Empty Lines: 0
Non-Domain-only Rules Excluded: 681
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 9
Domain-only Rules Output: 17319
```

&nbsp;

## NoCoin Filter List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/nocoin-justdomains.txt) |
| Pi-Hole | [nocoin-justdomains.txt](https://raw.githubusercontent.com/justdomains/blocklists/master/lists/nocoin-justdomains.txt) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 04 Feb 2018
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 139
Comment Lines: 12
Empty Lines: 3
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 124
```

&nbsp;

# Reporting Conversion Issues:
If you find an issue in the output of the conversion process (i.e. comparing to the original upstream list), please report it over on: https://github.com/justdomains/ci/issues

**NOTE: We do not manage the upstream lists themselves, and will not be able to add any new blocks to the lists.**

##### Disclaimer:
<sup>These files are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, arising from, out of or in connection with the files or the use of the files.</sup>

<sub>Any and all trademarks are the property of their respective owners.</sub>
