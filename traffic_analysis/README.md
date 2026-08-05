# malware_traffic

Analizy ruchu sieciowego (pcap) prowadzone w Wiresharku — identyfikacja zainfekowanych hostów, C2, użytkowników i śladów działania malware na podstawie przechwyconego ruchu.

## Analizy

| Data | Nazwa | Krótki opis |
|---|---|---|
| 2026-02-28 | [C2 traffic & user enumeration via SAMR](./2026-02-28-c2-samr-enum/writeup.md) | Identyfikacja zainfekowanego hosta na podstawie ruchu C2 (HTTP POST), namierzenie nazwy hosta (NBNS), nazwy użytkownika (Kerberos) oraz pełnych danych osobowych użytkownika (SAMR QueryUserInfo) |
| 2026-07-28 | [Restoring hashed password of infected user](./ntlm_auth/ntlm_auth.md) | Extracted a NetNTLMv2 hash from SMB traffic in Wireshark, pulled the username and domain from the authentication packet, and cracked the hash with hashcat (mode 5600) to recover the user's password. |
## Narzędzia

- Wireshark
