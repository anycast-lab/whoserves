# whoserves

Measure anycast catchments from the outside: which users are served by which
site of an anycast service, over IPv4 and IPv6, using public RIPE Atlas
measurements and the site identifiers the service returns (NSID,
`hostname.bind`).

**Status: early placeholder (0.0.1).** This release contains no measurement
code yet. It reserves the name for the open tooling that is being extracted
from the work published at <https://anycast.dev/notes>:

- catchment measurement of third-party anycast services, no operator access needed
- population-weighted results instead of raw probe counts
- failover order per zone: who carries it if the fastest operator is gone
- reproducible results: public measurement IDs, raw data, scripts

Project home: <https://anycast.org> · Source: <https://github.com/anycast-lab/whoserves>

```
pip install whoserves
whoserves
```

prints this notice. Licence: Apache-2.0.
