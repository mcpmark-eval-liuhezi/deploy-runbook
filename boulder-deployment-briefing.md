# Sensor Team Go/No-Go Briefing — Boulder Test Site Deployment

**Site:** Boulder, CO (40.01499, -105.27055)
**Prepared:** Tuesday, Nov 10, 2026 (11:46 PM local forecast update)
**Read-out:** For tomorrow's standup

---

## 1) 7-Day Forecast at the Site (temp / sky)

| Day | High / Low | Sky & Conditions | Precip | Wind |
|---|---|---|---|---|
| **Today (Veterans Day)** | 66 / 40°F | Sunny; clear tonight | 0% | 5 mph SSE |
| **Thu Nov 12** | **67 / 39°F** | **Sunny** | 0% | 1–6 mph SSE |
| **Fri Nov 13** | **66 / 39°F** | **Mostly Sunny** | 0% | 3 mph N |
| **Sat Nov 14** | 57 / 39°F | Partly sunny, **30% chance showers after 5 PM** | 30% | 0–3 mph NNE |
| **Sun Nov 15** | 56 / 38°F | Mostly Sunny | 11% | 0–3 mph N |
| **Mon Nov 16** | 59 / 38°F | Mostly Sunny | 0% | 2 mph N |
| **Tue Nov 17** | 60 / 39°F | Mostly sunny, ~26% chance showers after 5 PM | 26% | 2 mph NE |

**Workdown:** Earliest workable stretch is today/Thursday (sunny, highs 66–67°F, virtually calm). Saturday is the first degrade — 30% shower chance late in the day. Sunday and Monday stay dry with light winds; Tuesday grades back into similar shower risk as Saturday.

## 2) Date Pick: No Calendar Conflicts

Your connected work calendar shows no booked commitments in the next-seven-day window (Nov 10–17). The only entries on file are personal/clinical events from late June 2025, which don't overlap the deployment week. **All candidate days (Thu, Fri, Sun, Mon) are clear to deploy.**

## 3) Network Operator for AS14061 (Telemetry Relay)

Confirmed via ARIN WHOIS:

- **ASN:** AS14061 (ASName: DIGITALOCEAN-ASN)
- **Operator:** **DigitalOcean, LLC** (OrgId: DO-13), 105 Edgeview Drive, Suite 425, Broomfield, CO 80021, US
- **NOC / Main Contact:** noc@digitalocean.com, +1-646-827-4366
- **Abuse Contact:** abuse@digitalocean.com
- **Routing/Peering Policy:** https://www.as14061.net
- **RDAP:** https://rdap.arin.net/registry/autnum/14061

**Action:** Email DigitalOcean's NOC at **noc@digitalocean.com** to schedule our maintenance window on the telemetry relay path (AS14061).

## 4) Recommendation

### ✅ GO — Deploy Thursday, Nov 12, 2026

**Reasoning:**
1. **Best weather of the week:** Sunny all day, high 67°F (easiest for field work and sensor handling), light winds 1–6 mph SSE — essentially calm for launch sequences.
2. **Zero precipitation risk** (0%) vs 26–30% shower chances on Sat/Tue.
3. **Earliest possible date** gives a full buffer before any weekend degradation and keeps us clear of Sat's late-afternoon shower window (30% after 5 PM).
4. **Cold side is manageable:** overnight low ~39°F; bring layers, insulated enclosures, and battery blankets for discrete equipment.
5. **No calendar conflicts** confirmed for Thursday.
6. **Fallback order:** Friday (66°F, mostly sunny, 3 mph N) is essentially tied and acceptable if Thursday doesn't work; Sunday/Monday are solid alternates if we need a later slot.

**Caveats:** Thursday night will be breezier (~5 mph WSW), which is negligible. Avoid Saturday and Tuesday due to shower risk.

**Prepared by:** HeziLiu (GitHub: HeziLiu) for the sensor team standup.
