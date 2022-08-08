---
title: 'Security Bulletin: Multiple vulnerabilities in IBM Java Runtime affect z/TPF'
date: 2019-12-14T01:22:00+01:00
draft: false
---

#### Dec 11, 2019 7:01 pm EST | [High Severity](https://www.ibm.com/blogs/psirt/category/severity-high/)

CVEID:   CVE-2019-9515 DESCRIPTION:   Some HTTP/2 implementations are vulnerable to a settings flood, potentially leading to a denial of service. The attacker sends a stream of SETTINGS frames to the peer. Since the RFC requires that the peer reply with one acknowledgement per SETTINGS frame, an empty SETTINGS frame is almost equivalent in behavior to a ping. Depending on how efficiently this data is queued, this can consume excess CPU, memory, or both.CVSS Base score: 7.5CVSS Temporal Score: See: https://ift.tt/33UVWWM for the current score.CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) CVEID:   CVE-2019-9518 DESCRIPTION:   Some HTTP/2 implementations are vulnerable to a flood of empty frames, potentially leading to a denial of service. The attacker sends a stream of frames with an empty payload and without the end-of-stream flag. These frames can be DATA, HEADERS, CONTINUATION and/or PUSH\_PROMISE. The peer spends time processing each frame disproportionate to attack bandwidth. This can consume excess CPU.CVSS Base score: 7.5CVSS Temporal Score: See: https://ift.tt/2sO8135 for the current score.CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) CVEID:   CVE-2019-9517 DESCRIPTION:   Some HTTP/2 implementations are vulnerable to unconstrained interal data buffering, potentially leading to a denial of service. The attacker opens the HTTP/2 window so the peer can send without constraint; however, they leave the TCP window closed so the peer cannot actually write (many of) the bytes on the wire. The attacker then sends a stream of requests for a large response object. Depending on how the servers queue the responses, this can consume excess memory, CPU, or both.CVSS Base score: 7.5CVSS Temporal Score: See: https://ift.tt/2s73A37 for the current score.CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) CVEID:   CVE-2019-9512 DESCRIPTION:   Some HTTP/2 implementations are vulnerable to ping floods, potentially leading to a denial of service. The attacker sends continual pings to an HTTP/2 peer, causing the peer to build an internal queue of responses. Depending on how efficiently this data is queued, this can consume excess CPU, memory, or both.CVSS Base score: 7.5CVSS Temporal Score: See: https://ift.tt/2RwvtfQ for the current score.CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) CVEID:   CVE-2019-9514 DESCRIPTION:   Some HTTP/2 implementations are vulnerable to a reset flood, potentially leading to a denial of service. The attacker opens a number of streams and sends an invalid request over each stream that should solicit a stream of RST\_STREAM frames from the peer. Depending on how the peer queues the RST\_STREAM frames, this can consume excess memory, CPU, or both.CVSS Base score: 7.5CVSS Temporal Score: See: https://ift.tt/3517sRS for the current score.CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) CVEID:   CVE-2019-9513 DESCRIPTION:   Some HTTP/2 implementations are vulnerable to resource loops, potentially leading to a denial of service. The attacker creates multiple request streams and continually shuffles the priority of the streams in a way that causes substantial churn to the priority tree. This can consume excess CPU.CVSS Base score: 7.5CVSS Temporal Score: See: https://ift.tt/2LHciMy for the current score.CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) [...read more](https://www.ibm.com/blogs/psirt/security-bulletin-multiple-vulnerabilities-in-http-2-implementation-used-by-liberty-for-java-for-ibm-cloud/)

  
  
from IBM Product Security Incident Response Team https://ift.tt/2rNgaoe