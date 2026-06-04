# Hey there, I'm Hemanth Bommireddy 👋

PhD candidate in Astronomy at **Universidad de Chile**, working at the intersection of **multimessenger astronomy** and **alert broker infrastructure**.

My research focuses on searching for electromagnetic counterparts of gravitational wave events using real-time public alert streams from ZTF, LSST, and DECam — in an era where tens of thousands of transients arrive every night.

I build open-source tools to help the astronomy community navigate this flood of time-domain alerts.

---

## 🔭 Research

- **GW counterpart searches** — Crossmatching LIGO/Virgo/KAGRA skymaps with ZTF/ALeRCE alert streams to identify kilonova and AGN candidates
- **Kilonova simulations** — Monte Carlo rate estimation and detection efficiency studies for several Kilonova models
- **Alert broker infrastructure** — Building pipelines on top of ALeRCE, GCN Kafka streams, and GraceDB for real-time transient classification
- **Survey sensitivity** — ZTF-based kilonova rate upper limits benchmarked against LVK BNS merger rates

---

## 🛠️ Tech Stack

**Languages:** Python · TypeScript · SQL  
**Astronomy:** astropy · ligo.skymap · healpy · sncosmo · Redback  
**Brokers & Streams:** ALeRCE · GCN Kafka · GraceDB   
**Backend:** PostgreSQL  
**Frontend:** React · Vite · Recharts  
**DevOps:** GitHub Actions · Vercel  

---

##  Featured Projects

### [GW-AGN Watcher Dashboard](https://github.com/Hemanthb1/gw-agn-dashboard) · [Live Demo](https://gw-agn-dashboard.vercel.app)
Dashboard for GW follow-up — crossmatches LIGO/Virgo events with AGN candidates from ZTF/ALeRCE. Includes GW skymap overlays, ZTF light curves, and GraceDB integration.
> Contributed to NASA GCN codebase: [PR #3579](https://github.com/nasa-gcn/gcn.nasa.gov/pull/3579)

### [GW AGN Watcher Pipeline](https://github.com/Hemanthb1/GW_AGN_watcher)
Python pipeline for real-time GW skymap × ZTF alert crossmatching. Downloads skymaps from GraceDB, queries ALeRCE, crossmatches against the Milliquas AGN catalog, and ranks candidates by overlap probability.

---

##  PyPI Packages

Published open-source Python packages for the astronomy community → [pypi.org/user/hemanth195](https://pypi.org/user/hemanth195/)

---

## Publications & Academic Profile

- [InspireHEP](https://inspirehep.net/authors/2902490?ui-citation-summary=true)
- [ORCID](https://orcid.org/0009-0007-4271-6444)
