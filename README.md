# NSS-77TR RECORD V0.1.3


## V0.1.3 integrated release
- Full package rebuild.
- Storage key changed to `nss77tr_record_v013_release` so cleaned seed data loads fresh.
- Cache/version strings updated to V0.1.3 where available.
- Embedded cleaned RECORD JSON backup as seed data.
- Count logic scans date-title lines by record month.
- Old divider bars around logs are ignored.
- Other-month logs accidentally attached to a month block are ignored for render/count.
- Daily titles accept both em dash and plain hyphen.
- Explicit Rest / Delay logs are separated.
- If no explicit Rest / Delay logs exist, rest/delay is month days minus sessions.
- Archive/detail metadata displays `N sessions · M rest/delay`.
- Session time remains non-bold.
