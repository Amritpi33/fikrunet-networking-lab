# Validation Checklist

1. From each LAN host, ping its default gateway (IPv4 & IPv6).
2. Verify inter‑site routing: ping between Site 3 hosts and Site 1/2/4.
3. On routers/switches, run:
   ```
   show ip interface brief
   show ipv6 interface brief
   show ip route
   show ipv6 route
   ```
4. Capture successful ping + interface outputs into `screenshots/`.
