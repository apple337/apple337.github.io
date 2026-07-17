# malware_traffic

Analizy ruchu sieciowego (pcap) prowadzone w Wiresharku — identyfikacja zainfekowanych hostów, C2, użytkowników i śladów działania malware na podstawie przechwyconego ruchu.

## Analizy

| Data | Nazwa | Krótki opis |
|---|---|---|
| 2026-02-28 | [C2 traffic & user enumeration via SAMR](./2026-02-28-c2-samr-enum/writeup.md) | Identyfikacja zainfekowanego hosta na podstawie ruchu C2 (HTTP POST), namierzenie nazwy hosta (NBNS), nazwy użytkownika (Kerberos) oraz pełnych danych osobowych użytkownika (SAMR QueryUserInfo) |

## Narzędzia

- Wireshark
