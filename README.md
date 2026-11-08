# Favian Izza

Software engineer. Information Systems & Technology (Cum Laude), Bandung Institute of Technology. [Portfolio](https://favianizza.space) · [Email](mailto:izza.diasputra10@gmail.com) · [LinkedIn](https://www.linkedin.com/in/favianizza/)

- [**netflow**](https://github.com/favizz/netflow): replaces a manual process, staff photographing 2,444+ apartment water and electricity meters every month and typing the readings in by hand, with live MQTT telemetry streamed straight into prepaid billing. Residents top up from their phones, and a 13-detector anomaly engine flags tampering as it happens instead of waiting for next month's inspection, backed by 166 unit tests and a real CI pipeline (lint, test, build on every push). NestJS and MySQL backend, originally an undergraduate thesis project.
- [**CrowdEase**](https://github.com/favizz/Portofavolio): a real planning question, where TransJakarta's bus network has coverage gaps, that a naive search would need about 130 million distance calculations to answer. A Go spatial-hash walkshed engine makes that practical: real 500m coverage computed for all 8,091 stops on TransJakarta's own published GTFS feed, 240 routes. A batched ingestion pipeline loads about 252,000 real GTFS rows into Postgres in under 600 round trips instead of one row at a time. [Demo](https://portofavolio-rmww.vercel.app)
- [**genyra-familytree**](https://github.com/favizz/genyra-familytree): replaces manual spreadsheets and photos for one real family's genealogy records with an interactive family tree. A custom multi-phase auto-layout engine positions members across generations automatically, including multi-marriage cases that used to need manual placement. BFS-based consanguinity checks flag close-relative conflicts up to 3 generations before a relationship can be saved. [Demo](https://genyra.vercel.app)

<!--
Gap against the benchmarked profiles (Meta/Anthropic/Google/OpenAI engineers): none of the above has been adopted or used by people outside my own team, thesis, or one family. Their strongest bullets cite real external usage (a library with six-figure downloads, code running in another company's production) or a citable paper. The next project worth adding here is one with a real stranger using it, not another solo or team build.
-->

## Experience

<table width="100%">
<tr>
<td align="center" width="33%"><img src="assets/siemens.webp" width="90"></td>
<td align="center" width="33%"><img src="assets/toyota.svg" width="50"></td>
<td align="center" width="33%">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/trich-dark.webp">
  <img src="assets/trich.webp" width="64">
</picture>
</td>
</tr>
<tr>
<td align="center"><b>Siemens Indonesia</b><br><sub>Software Developer Intern</sub></td>
<td align="center"><b>Toyota Astra</b><br><sub>Software Engineer Intern</sub></td>
<td align="center"><b>Trich AI Barberspace</b><br><sub>Front-End Developer, Part-Time</sub></td>
</tr>
<tr>
<td>Maintained a Laravel factory visitor and access system used daily by 200+ personnel.</td>
<td>Built an asset management system tracking 7,000+ IT assets.</td>
<td>Built and launched the public website end to end with Next.js.</td>
</tr>
</table>

## Recognition

- GEMASTIK XVIII, Best Paper, Smart City track, a national computing competition run by Indonesia's Ministry of Higher Education
- COMPFEST XVII, Top 8 Finalist, AI Innovation Challenge, hosted by the University of Indonesia
- BSI Scholarship Talenta Awardee, from one of Indonesia's largest Islamic banks

<!--
Gap against the benchmarked profiles: the GEMASTIK Best Paper award has no public, citable writeup (no arXiv-equivalent link), unlike the published/cited work on the benchmarked profiles. Worth writing up and linking here if the paper itself is shareable.
-->
