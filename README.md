```nasm
; =====================================================================
;  sub_401000  whoami()                                   Rio de Janeiro
; =====================================================================
00401000   mov   name,   "Marcos Tolosa"
00401005   mov   handle, "Tr0p"
0040100A   mov   role,   "red team · exploit dev · reverse engineering"
0040100F   mov   loop,   "break → understand → automate → teach"
00401014   ret
```

### `disclosures()`

```nasm
00401140   CVE-2025-10230    samba    "OS command injection"          ; CVSS 10.0 · hidden 13 years
00401168   CVE-2026-23722    wegia    "stored XSS → RCE"              ; CVSS 9.1
00401190   CVE-2025-67503    wegia    "reflected XSS"                 ; CVSS 8.2
004011B8   NCUA VDP          us_gov   "unauth OS command injection"   ; P1
004011E0   Digital Flanders  be_gov   "blind XXE → internal SSRF"     ; High
00401208   Samba CTDB        samba    "buffer overflow"               ; InfiniBand wrapper, sprintf()
```
<sub>xrefs → [CVE-2025-10230](https://aisle.com/blog/cve-2025-10230-the-cvss-100-vulnerability-that-hid-in-samba-for-13-years) · [CVE-2026-23722](https://github.com/LabRedesCefetRJ/WeGIA/security/advisories/GHSA-g7hh-6qj7-mcqf) · [CVE-2025-67503](https://github.com/LabRedesCefetRJ/WeGIA/security/advisories/GHSA-r9mh-4hc4-h2p3) · [NCUA](https://bugcrowd.com/engagements/ncua-vdp/crowdstream) · [Flanders](https://yeswehack.com/programs/digital-flanders-vulnerability-disclosure-program#program-activity) · [Samba MR](https://gitlab.com/samba-team/samba/-/merge_requests/4240/diffs?commit_id=caa2ac41bf25c524cbe5079a450d87f30a25b0a2)</sub>

### `hall_of_fame()`

```nasm
00401300   push  "NASA"
00401305   push  "U.S. Dept. of Commerce"
0040130A   push  "Dept. of Veterans Affairs"
0040130F   push  "NCUA"
00401314   push  "EPA"
00401319   push  "U.S. Fish & Wildlife Service"
0040131E   call  bugcrowd.com/h/Tr0p            ; 6× U.S. Gov · 15 valid · 93.75% accuracy
```

### `tools()`

| symbol | does |
|---|---|
| [`manw_ng`](https://github.com/marcostolosa/manw-ng) | Win32/NTAPI docs + live ctypes execution, for reversers |
| [`ocrack`](https://github.com/marcostolosa/OCRack) | PDF translate + OCR, layout intact |
| [`arctax`](https://github.com/marcostolosa/arctax) | prompt-injection research generator |
| [`reload_me`](https://github.com/mindsecurity/REload.Me) | learn RE the simple way |

### `imports()`

```
IDA Pro · Ghidra · Rizin · x64dbg · Frida · pwndbg · BloodHound · Impacket · Certipy
Rubeus · Havoc · Cobalt Strike · Burp Pro · pwntools · Semgrep · CodeQL · nuclei · ffuf
python · go · c/c++ · bash · powershell
```

<img src="./github-metrics.svg" alt="GitHub activity metrics" width="100%">

### `connect()`

[mindsecurity.org](https://mindsecurity.org) · [writeups](https://mindsecurity.org/writeups/) · [bugcrowd](https://bugcrowd.com/h/Tr0p) · [linkedin](https://www.linkedin.com/in/marcos-tolosa/) · [youtube](https://youtube.com/@Marcos.Tolosa) · [x](https://twitter.com/MarcosTolosa_) · [discord](https://discord.gg/T9RVG3re2J) · `marcos.tolosa@owasp.org`

<sub>`; authorized targets only`</sub>
