# Favian Izza

Software engineer. Information Systems & Technology (Cum Laude), Bandung Institute of Technology. [Portfolio](https://favianizza.space) · [Email](mailto:izza.diasputra10@gmail.com) · [LinkedIn](https://www.linkedin.com/in/favianizza/)

- [**Portofavolio**](https://github.com/favizz/Portofavolio): transit analytics platform on TransJakarta's real GTFS feed, 240 routes and 8,091 stops. Built a Go spatial-hash walkshed engine that computes real 500m coverage for every stop, avoiding a roughly 130 million calculation naive nearest-stop search. A batched ingestion pipeline loads about 252,000 real GTFS rows into Postgres in under 600 round trips. Live rider demo replays real buses along their real routes and estimates ride times, labeled as an estimate, not measured ridership. [Demo](https://portofavolio-rmww.vercel.app)
- [**Fraud-Detection-using-Machine-Learning-Algorithm**](https://github.com/favizz/Fraud-Detection-using-Machine-Learning-Algorithm): Decision Tree, Logistic Regression, and KNN implemented from scratch by a 4-person team on a real, severely imbalanced dataset (about 100k transactions, 14% fraud), benchmarked against scikit-learn. Class weighting and SMOTE took fraud recall from 0.02 to 0.52, a 25x cut in false negatives. My part: the preprocessing pipeline, EDA, the scikit-learn benchmark implementations, and the live demo web app. [Demo](https://fraud-detection-using-machine-learn.vercel.app)
- [**netflow**](https://github.com/favizz/netflow): IoT prepaid utility metering, originally an undergraduate thesis project. NestJS and MySQL stream live MQTT telemetry from 2,444+ smart meters into prepaid billing. A 13-detector anomaly engine (backflow, tamper, sensor faults, MCB trips) is backed by 166 unit tests.
- [**genyra-familytree**](https://github.com/favizz/genyra-familytree): genealogy platform on a shared-type monorepo. A custom multi-phase auto-layout engine positions family members across generations without manual placement, handling multi-marriage cases. BFS-based consanguinity checks flag close-relative conflicts up to 3 generations before a relationship can be saved. [Demo](https://genyra-familytree.vercel.app)

<!--
Gap against the benchmarked profiles (Meta/Anthropic/Google/OpenAI engineers): none of the above has been adopted or used by people outside my own team or coursework. Their strongest bullets cite real external usage (a library with six-figure downloads, code running in another company's production) or a citable paper. The next project worth adding here is one with a real stranger using it, not another solo or team build.
-->

**Experience**: Software Developer Intern, PT Siemens Indonesia, maintained a Laravel factory visitor and access system used daily by 200+ personnel. Software Engineer Intern, PT Toyota Astra Motor, built an asset management system tracking 7,000+ IT assets. Regulatory Analyst Intern, PT Toyota Motor Manufacturing Indonesia, built a Python/OCR pipeline reconciling 8,000+ customs records, cutting manual effort 70%+.

**Recognition**: Best Paper, Smart City track, GEMASTIK XVIII (national-level, Kemendiktisaintek RI). Top 8 Finalist, AI Innovation Challenge, COMPFEST XVII (Universitas Indonesia). BSI Scholarship Talenta Awardee, Bank Syariah Indonesia.

<!--
Gap against the benchmarked profiles: the GEMASTIK Best Paper award has no public, citable writeup (no arXiv-equivalent link), unlike the published/cited work on the benchmarked profiles. Worth writing up and linking here if the paper itself is shareable.
-->
