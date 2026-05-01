<div align="center">

<img src="assets/logos/f1.svg" width="160" alt="F1 Logo">

<br>

# Awesome F1

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of high-quality Formula 1 and motorsport resources — APIs, datasets, telemetry tools, visualization projects, sim racing, and learning materials.

</div>

---

## Contents

- [Formula 1](#formula-1)
  - [APIs and Libraries](#apis-and-libraries)
  - [Datasets and Telemetry Archives](#datasets-and-telemetry-archives)
  - [Kaggle Datasets](#kaggle-datasets)
  - [Live Timing](#live-timing)
  - [Tools and Apps](#tools-and-apps)
  - [Dashboards and Analytics](#dashboards-and-analytics)
  - [Calendar](#calendar)
  - [Fantasy F1](#fantasy-f1)
  - [Prediction and Machine Learning](#prediction-and-machine-learning)
  - [Simulation and Vehicle Dynamics](#simulation-and-vehicle-dynamics)
  - [Historical and Statistics](#historical-and-statistics)
  - [Official and Reference](#official-and-reference)
  - [News and Media](#news-and-media)
  - [Technical Media](#technical-media)
  - [Junior and Feeder Series Media](#junior-and-feeder-series-media)
  - [Official Session Sources](#official-session-sources)
- [Formula 2 and Formula 3](#formula-2-and-formula-3)
- [Formula E](#formula-e)
- [Endurance, WEC, Le Mans, IMSA](#endurance-wec-le-mans-imsa)
- [WRC and Rally](#wrc-and-rally)
- [MotoGP and WorldSBK](#motogp-and-worldsbk)
- [NASCAR](#nascar)
- [IndyCar](#indycar)
- [Other Series](#other-series)
- [Sim Racing](#sim-racing)
- [Cross-Series and General Motorsport](#cross-series-and-general-motorsport)
- [Learning and Education](#learning-and-education)
  - [Books](#books)
  - [Blogs and Tutorials](#blogs-and-tutorials)
  - [YouTube Channels](#youtube-channels)
  - [Podcasts](#podcasts)
- [Films, Documentaries, and Games](#films-documentaries-and-games)
- [Official Reference Links](#official-reference-links)

---

## Formula 1

### APIs and Libraries

- [FastF1](https://github.com/theOehrly/Fast-F1) - Python library for timing, telemetry, weather, sessions, and strategy analysis. The de facto standard for F1 data in Python.
- [FastF1 Docs](https://docs.fastf1.dev/) - Primary documentation for F1 analysis workflows in Python.
- [OpenF1](https://openf1.org/) - Open API for lap data, positions, team radio, stints, weather, and sessions.
- [OpenF1 GitHub](https://github.com/br-g/openf1) - Source and docs for OpenF1.
- [Jolpica-F1](https://github.com/jolpica/jolpica-f1) - Ergast-compatible F1 API and the current community standard replacement since Ergast shutdown.
- [Jolpica API](https://api.jolpi.ca/ergast/f1/) - Hosted endpoint for historical F1 data.
- [F1DB](https://github.com/f1db/f1db) - Full F1 database distributed as JSON, CSV, and SQL dumps.
- [LiveF1](https://github.com/GoktugOcal/LiveF1) - Python toolkit for real-time and historical F1 data with medallion architecture ETL.
- [f1dataR](https://github.com/SCasanova/f1dataR) - R package wrapping FastF1 and Jolpica. The standard R interface for F1 data.
- [f1api.dev](https://f1api.dev/) - Developer-focused F1 API and SDK surface. [GitHub](https://github.com/rafacv23/f1-api).
- [F1PyStats](https://github.com/alec-kr/F1PyStats) - Python package for standings, race results, and historical summaries.
- [API-Sports Formula 1](https://api-sports.io/documentation/formula-1/v1) - Commercial API with free tier (100 req/day), covering seasons, standings, and results.

### Datasets and Telemetry Archives

- [Tracing Insights Archive](https://github.com/TracingInsights-Archive) - Season-by-season telemetry CSV archives.
- [Tracing Insights Data](https://tracinginsights.com/data/) - Download hub for telemetry and session data.
- [TracingInsights on HuggingFace](https://huggingface.co/datasets/tracinginsights/RaceData) - Full Ergast-schema mirror with 20+ CSV files, auto-updated within 3 hours of each race.
- [renumics/f1_dataset](https://huggingface.co/datasets/renumics/f1_dataset) - Montreal 2023 GP telemetry with 40+ columns including 882-dimensional embeddings for ML.
- [formula1-datasets](https://github.com/toUpperCase78/formula1-datasets) - Season-by-season CSV datasets and Jupyter analysis notebooks for every F1 season from 2019-2026. Actively updated after each race.
- [f1-circuits](https://github.com/bacinger/f1-circuits) - F1 circuits in GeoJSON format with track layouts and location coordinates. 35+ of 77 historic circuits.
- [TUMFTM/racetrack-database](https://github.com/TUMFTM/racetrack-database) - Center lines, track widths, and computed race lines for 20+ circuits from TU Munich.
- [RelBench rel-f1](https://relbench.stanford.edu/datasets/rel-f1/) - Stanford relational ML benchmark with 9 tables, 97K+ rows, and 6 ML tasks covering 1950-present. NeurIPS 2024.

### Kaggle Datasets

- [F1 World Championship 1950-2024](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020) - The canonical Kaggle F1 dataset by Rohan Rao. 14 CSV tables sourced from Ergast. 153K+ downloads.
- [Formula 1 Race Data](https://www.kaggle.com/datasets/jtrotman/formula-1-race-data) - Actively maintained post-Ergast shutdown via Jolpica. Covers 1950 to current race. 7.7K+ downloads.
- [F1 Drivers Dataset](https://www.kaggle.com/datasets/dubradave/formula-1-drivers-dataset) - All F1 drivers from Wikipedia with career stats. 4.6K+ downloads.

### Live Timing

- [undercut-f1](https://github.com/JustAman62/undercut-f1) - TUI live timing app with variable delay (sync to TV broadcast), session replay, and team radio transcription.
- [MultiViewer for F1](https://multiviewer.app) - Desktop app for synced live timing, mini sectors, and speeds. Requires F1 TV subscription.
- [F1 Pitwall](https://f1pitwall.fun/) - Live race replay and telemetry dashboard in the browser.

### Tools and Apps

- [F1 Replay Timing](https://github.com/adn8naiagent/F1ReplayTiming) - Replay viewer with timing overlays, telemetry charts, and track map support.
- [f1_sensor](https://github.com/Nicxe/f1_sensor) - Home Assistant integration with next race, calendar, live flags, Race Control messages, weather, standings, and historical results.
- [f1-sensor-live-data-card](https://github.com/Nicxe/f1-sensor-live-data-card) - Home Assistant cards for live F1 telemetry and championship views.
- [formulaone-card](https://github.com/marcokreeft87/formulaone-card) - Home Assistant dashboard card for F1 standings, schedules, and results. Works with Jolpica API or f1_sensor.
- [Apify F1 Data Extractor](https://apify.com/richard.biros/f1-data-extractor) - Scrapes formula1.com for race, qualifying, practice, and pit stop data from 1950-present. Clean JSON output.
- [F1AppleTV](https://github.com/NoahFetz/F1AppleTV) - F1TV client for Apple TV with multi-feed viewing and multiple audio tracks.
- [BoxBox](https://github.com/BrightDV/BoxBox) - Open-source F1 and Formula E mobile app (Flutter). News, standings, schedule, offline mode. Available on F-Droid.
- [RaceControl](https://github.com/robvdpol/RaceControl) - F1TV desktop client for Windows (.NET) with built-in or external player support. `archived`
- [f1viewer](https://github.com/SoMuchForSubtlety/f1viewer) - TUI for F1TV in Go supporting VOD and live streaming via MPV. `archived`

### Dashboards and Analytics

**Web platforms:**

- [F1 Cosmos](https://f1cosmos.com/) - Comprehensive F1 data dashboard with rich visualizations and race analytics.
- [F1 The Data](https://f1thedata.com/) - F1 data platform with driver comparisons, telemetry analysis, and historical data exploration.
- [Pitwall](https://pitwall.app/) - F1 database with lap data, pitstop data, race progression from 1950. Web + iOS.
- [F1 DataStop](https://f1datastop.com/) - Lap time deltas, stint strategy breakdowns, driver vs teammate comparisons.
- [F1pace](https://f1pace.com/) - In-depth F1 data analysis and visualization.
- [BoardF1](https://boardf1.com/) - Real-time F1 analytics dashboard with race results, lap times, tyre strategy, and team pace.
- [Formula-Timer](https://formula-timer.com/) - Live timing and analytics with lap time breakdowns, performance insights, and circuit guide.
- [F1 Tempo](https://www.f1-tempo.com/) - Explore and compare F1 lap times and telemetry for journalists, analysts, and enthusiasts.
- [Formula Live Pulse](https://www.f1livepulse.com/) - Live timing with telemetry charts, 3D track map, AI assistant, and team radio. Covers F1, F2, F3, and F1 Academy.

**Open source:**

- [F1 Race Replay](https://github.com/IAmTomShaw/f1-race-replay) - F1 replay and telemetry app with track rendering and rich race-state visualization.
- [f1-dash](https://github.com/slowlydev/f1-dash) - Real-time F1 dashboard (Next.js) showing leaderboard, tires, gaps, laps, mini sectors. Live at [f1-dash.vercel.app](https://f1-dash.vercel.app/).
- [F1ReplayTiming](https://github.com/adn8naiagent/F1ReplayTiming) - Full-stack replay and live timing app with track map, telemetry overlays, and synchronized playback.
- [Armchair Strategist](https://github.com/Casper-Guo/Armchair-Strategist) - Strategy-focused F1 dashboard for pit windows, pace comparison, and race narrative visualization.
- [f1-live-data](https://github.com/f1stuff/f1-live-data) - Real-time F1 visualization using FastF1 live timing, InfluxDB, and Grafana.

### Calendar

- [F1 Calendar](https://github.com/sportstimes/f1) - Open-source Next.js F1 calendar app with email reminders and web push. Live at [f1calendar.com](https://f1calendar.com).

### Fantasy F1

- [F1 Fantasy API (Postman docs)](https://documenter.getpostman.com/view/11462073/TzY68Dsi) - REST API documentation for the official F1 Fantasy undocumented API.
- [Fantasy F1 API Endpoints Cheat Sheet](https://cheatography.com/sertalpbilal/cheat-sheets/fantasy-f1-api-endpoints/) - Comprehensive endpoint reference.
- [F1 Fantasy Tools](https://f1fantasytools.com/) - Monte Carlo simulation-based team calculator, budget builder, and live scoring for official F1 Fantasy.
- [F1 Pitwall.dev](https://f1pitwall.dev/) - Fantasy optimizer using FP/qualifying data with Monte Carlo confidence intervals. 80.6% backtest accuracy.

### Prediction and Machine Learning

- [f1ml](https://github.com/Jared-Chan/f1ml) - Lap-by-lap prediction: lap times, positions, pit stops, and collisions for 20 drivers through a full race. `archived`

### Simulation and Vehicle Dynamics

- [fastest-lap](https://github.com/juanmanzanero/fastest-lap) - Vehicle dynamics simulator for optimal lap-time simulation with 3DOF/6DOF models (C++/Python).
- [TUMFTM/global_racetrajectory_optimization](https://github.com/TUMFTM/global_racetrajectory_optimization) - Minimum curvature and minimum time racing line generation from TU Munich. Published research.
- [TUMFTM/race-simulation](https://github.com/TUMFTM/race-simulation) - Lap-wise race simulation for pit stop strategy with reinforcement learning and Monte Carlo analysis.

### Historical and Statistics

- [F1 BigData](https://www.bigdataf1.com/) - Comprehensive historical statistics database, 1950 to present.
- [Formula 1 Archive](https://www.formula1archive.com/) - Complete F1 history: 1,100+ races, 900+ drivers, 75+ seasons.
- [f1metrics](https://f1metrics.wordpress.com/) - Mathematical and statistical F1 modeling, driver performance ratings, and deep analysis.
- [F1 Analysis](https://f1-analysis.com/) - Mathematical and statistical F1 analytics with predictive models.
- [OldRacingCars.com](https://www.oldracingcars.com/f1/) - Detailed chassis-level histories for 3-litre F1 cars (1966-1985) with non-championship race results.
- [x1z.net](https://x1z.net/) - Searchable index of the F1 TV archive with race ratings and session links.
- [Formula1Points.com](https://www.formula1points.com/) - Compare drivers across different points systems. Head-to-head stats and alternative scoring scenarios.
- [4mula1stats.com](https://www.4mula1stats.com/) - F1 results, statistics, and charts since 1950 with driver comparison tools.

### Official and Reference

- [F1 Live Timing](https://www.formula1.com/en/timing/f1-live) - Official live timing hub.
- [F1 Schedule](https://www.formula1.com/en/racing/2026.html) - Official calendar.
- [F1 Results](https://www.formula1.com/en/results.html) - Official results and standings hub.
- [F1 Teams](https://www.formula1.com/en/teams.html) - Official team directory.
- [F1 Drivers](https://www.formula1.com/en/drivers.html) - Official driver directory.
- [FIA Formula 1 Regulations](https://www.fia.com/regulation/category/29) - Official sporting and technical regulations.
- F1 Social - [YouTube](https://www.youtube.com/@Formula1) / [Instagram](https://www.instagram.com/f1/) / [TikTok](https://www.tiktok.com/@f1) / [X](https://x.com/F1) / [Facebook](https://www.facebook.com/Formula1) / [Threads](https://www.threads.net/@f1)

#### Teams (2026)

| | |
|:--|:--|
| [Aston Martin Aramco Formula One Team](https://www.astonmartinf1.com/) | [Atlassian Williams F1 Team](https://www.williamsf1.com/) |
| [Audi Revolut F1 Team](https://www.sauber-group.com/motorsport/formula-1/) | [BWT Alpine Formula One Team](https://www.alpine-cars.com/f1) |
| [Cadillac Formula 1 Team](https://www.cadillacf1.com/) | [McLaren Mastercard F1 Team](https://www.mclaren.com/racing/) |
| [Mercedes-AMG PETRONAS Formula One Team](https://www.mercedesamgf1.com/) | [Oracle Red Bull Racing](https://www.redbullracing.com/) |
| [Scuderia Ferrari HP](https://www.ferrari.com/en-EN/formula1) | [TGR Haas F1 Team](https://www.haasf1team.com/) |
| [Visa Cash App Racing Bulls](https://www.racingbulls.com/) | |

### News and Media

- [Formula 1 Latest](https://www.formula1.com/en/latest) - Official F1 news, videos, standings, results, and paddock analysis.
- [Autosport Formula 1](https://www.autosport.com/f1/news/) - Established motorsport journalism since 1950 covering F1 news, features, calendar, standings, results, and live coverage.
- [Motorsport.com Formula 1](https://www.motorsport.com/f1/news/) - High-volume global F1 coverage with news, live text, schedules, results, standings, galleries, and video.
- [The Race Formula 1](https://www.the-race.com/category/formula-1/) - Independent F1 news, analysis, rule-change coverage, podcasts, and expert columns.
- [PlanetF1](https://www.planetf1.com/) - F1-focused news, live coverage, standings, schedule, data, tech, and community forum.
- [RaceFans](https://www.racefans.net/) - Independent F1 and motorsport coverage with news, race data, statistics, penalty points, Rate the Race, and forums.
- [RacingNews365](https://racingnews365.com/) - F1-focused daily news, calendar, results, standings, and race-weekend coverage.
- [Motor Sport Magazine F1](https://www.motorsportmagazine.com/articles/category/single-seaters/f1/) - Long-form F1 features, history, archives, statistics, and columns from a heritage motorsport publication.

### Technical Media

- [Auto Motor und Sport Formel 1](https://www.auto-motor-und-sport.de/formel-1/aktuell/) - German-language F1 reporting with strong paddock, interview, and technical coverage.
- [Racecar Engineering Formula One](https://www.racecar-engineering.com/formulaone/) - Technical and engineering-focused F1 articles, explainers, and car development coverage.
- [Giorgio Piola's F1 Technical Analysis](https://www.motorsport.com/topic/giorgio-piola-s-f1-technical-analysis/23/) - Technical illustrations and analysis from one of F1's best-known technical journalists.
- [SomersF1](https://somersf1.substack.com/) - Matthew Somerfield's technical F1 analysis and document-cache notes.

### Junior and Feeder Series Media

- [Formula Scout](https://formulascout.com/) - Junior single-seater news and features covering F2, F3, F4, Road to Indy, and future F1 prospects.
- [Feeder Series](https://feederseries.net/) - Junior single-seater previews, reviews, results, standings, podcasts, and driver-development coverage.

### Official Session Sources

- [FIA F1 Decision Documents](https://www.fia.com/documents/championships/fia-formula-one-world-championship-14/season/season-2026-2072) - Official race documents, steward decisions, race director notes, timetables, classifications, and technical notices.
- [FIA F1 Press Conference Transcripts](https://www.fia.com/news?category=Formula%201) - Official FIA-hosted F1 press conference transcripts and FIA news.
- [Pirelli F1 Press Area](https://press.pirelli.com/en/?h=1&t=formula+1) - Official tyre compound nominations, race previews, infographics, and tyre-related session reports.

## Formula 2 and Formula 3

- [FIA Formula 2 Event API](https://api.fia.com/events/formula-2-championship/) - FIA event documents and championship metadata.
- [FIA Formula 2](https://www.fiaformula2.com/) - Official site with [calendar](https://www.fiaformula2.com/Calendar), [standings](https://www.fiaformula2.com/Standings/Driver), and [regulations](https://www.fiaformula2.com/About/DyImndAsBNFcqYOOm4yWS/the-regulations-f2).
- [FIA Formula 3](https://www.fiaformula3.com/) - Official site with [calendar](https://www.fiaformula3.com/Calendar) and [regulations](https://www.fiaformula3.com/About/6Iosy860VzDs0INyfKw37E/the-rules-and-regulations-f3).

## Formula E

- [FIA Formula E Event API](https://api.fia.com/events/abb-fia-formula-e-world-championship/) - FIA event data.
- [Sportradar Formula E API](https://developer.sportradar.com/racing/reference/formula-e-seasons) - Commercial Formula E coverage.
- [TheSportsDB Formula E](https://www.thesportsdb.com/league/4371-formula-e) - Free general sports API entry.
- [Formula E](https://fiaformulae.com/) - Official site. [Rules](https://fiaformulae.com/en/championship/rules-and-regulations). [Teams](https://fiaformulae.com/en/teams).

## Endurance, WEC, Le Mans, IMSA

- [Al Kamel Systems](https://alkamelsystems.com/) - Industry-standard timing provider used across endurance racing. [WEC timing host](http://fiawec.alkamelsystems.com/).
- [IMSA GTP Telemetry](https://www.imsa.com/gtp-telemetry/) - Official telemetry-oriented reference for IMSA's top class.
- [FIA WEC](https://www.fiawec.com/) - Official site. [Regulations](https://www.fiawec.com/en/page/regulations-1). [Event API](https://api.fia.com/events/world-endurance-championship/).
- [24 Hours of Le Mans](https://www.24h-lemans.com/) - Official Le Mans site.
- [IMSA](https://www.imsa.com/) - Official site. [Schedule](https://www.imsa.com/weathertech/weathertech-2026-schedule/). [Regulations](https://www.imsa.com/competitors/2025-imsa-rules-regulations/).

## WRC and Rally

- [WRC Results API](https://api.wrc.com/results-api) - Stage times, split times, itinerary, car entries, classifications via JSON. Undocumented but reverse-engineered.
- [RallyDataJunkie](https://rallydatajunkie.com/visualising-wrc-rally-results/) - Online book documenting WRC API endpoints, data wrangling, and visualization.
- [eWRC-results.com](https://ewrc-results.com/) - Comprehensive rally database from 1911 to present, covering WRC down to national rallies.
- [FIA WRC Event API](https://api.fia.com/events/world-rally-championship/) - FIA event documents and championship metadata.
- [Sportradar Rally API](https://developer.sportradar.com/racing/reference/rally-overview) - Commercial API with schedules and post-race results for WRC.
- [WRC](https://www.wrc.com/) - Official site.
- [FIA World Rallycross](https://www.fiaworldrallycross.com/) - Official WRX results and standings.

## MotoGP and WorldSBK

- [TheSportsDB MotoGP](https://www.thesportsdb.com/league/4407-motogp) - Free community API surface.
- [TheSportsDB WorldSBK](https://www.thesportsdb.com/league/4454-sbk) - Free community API surface.
- [MotoGP](https://www.motogp.com/) - Official site. [Calendar](https://www.motogp.com/en/calendar/2026).
- [FIM Grand Prix Regulations](https://www.fim-moto.com/en/documents/view/fim-2026-motogp-moto2-moto3-world-championship-regulations) - Official rules PDF.
- [WorldSBK](https://www.worldsbk.com/) - Official site.

## NASCAR

- [NASCAR Feed API](https://feed.nascar.com/swagger/ui/index) - Official public API for schedules, entries, standings, and race data.
- [nascaR.data](https://cran.r-project.org/web/packages/nascaR.data/index.html) - R package for historical NASCAR datasets. Cup (1949+), Xfinity (1982+), Trucks (1995+). Auto-updated weekly.
- [Racing-Reference](https://www.racing-reference.info/) - Comprehensive NASCAR and motorsport historical statistics with loop data.
- [SportsDataIO NASCAR](https://sportsdata.io/nascar-motorsports-api) - Commercial NASCAR API.
- [Sportradar Racing API](https://developer.sportradar.com/racing) - Commercial racing API with NASCAR coverage.
- [NASCAR](https://www.nascar.com/) - Official site. [Cup Schedule](https://www.nascar.com/nascar-cup-series/2026/schedule/).

## IndyCar

- [Sportradar IndyCar API](https://developer.sportradar.com/racing/reference/indycar-statistics-summary) - Commercial IndyCar coverage.
- [TheSportsDB IndyCar](https://www.thesportsdb.com/league/4373-indycar-series) - Free general sports API with IndyCar coverage.
- [IndyCar](https://www.indycar.com/) - Official site. [Rulebook](https://epaddock.indycar.com/docs/default-source/rules-regulations-and-policies/indycar-rulebook.pdf).

## Other Series

- [DTM](https://www.dtm.com/en) - Official site with results, standings, and schedules. [Motorsport Stats](https://motorsportstats.com/series/deutsche-tourenwagen-masters/summary/2024).
- [Super Formula](https://superformula.net/sf2/en/) - Official results, standings, and schedule.
- [Super GT Results](https://supergt.net/results?ln=en) - Official GT500/GT300 results.
- [Supercars Live Timing](https://www.supercars.com/live-timing) - Official live timing during events. [TheSportsDB](https://www.thesportsdb.com/league/4489-V8-Supercars).
- [TouringCars.Net Database](https://www.touringcars.net/database/) - BTCC data from 1979-present, TCR series results, driver stats.

## Sim Racing

- **Cross-Platform**
  - [SimHub](https://github.com/SHWotever/SimHub) - Industry-standard multi-sim dashboard, bass shaker driver, and plugin platform.
  - [MoTeC i2](https://www.motec.com.au/i2/i2downloads/) - Professional telemetry analysis from real-world motorsport. i2 Standard is free.
  - [Grafana Simracing Telemetry](https://github.com/alexanderzobnin/grafana-simracing-telemetry) - Grafana data source plugin for visualizing telemetry from ACC and iRacing.
  - [RaceLab](https://racelab.app/) - Commercial overlay app with free tier for iRacing, ACC, rF2, LMU, AMS2, F1.
- **iRacing**
  - [pyirsdk](https://github.com/kutu/pyirsdk) - Python 3 iRacing SDK for live telemetry, session data, and broadcast commands.
  - [iracingdataapi](https://github.com/jasondilworth56/iracingdataapi) - Python wrapper for iRacing /data API with rate limit tracking.
  - [pyracing](https://github.com/Esterni/pyracing) - Async Python API client mapping iRacing JSON to structured objects.
  - [ibt-telemetry](https://github.com/SkippyZA/ibt-telemetry) - 100% complete IBT parser, cross-platform. Node.js.
  - [Cosworth Pi Toolbox](https://www.iracing.com/cosworth-pi-toolbox/) - Professional-grade data analysis. Reads IBT natively. Free Lite tier.
  - [iRacing Developers](https://members-ng.iracing.com/data-api/about) - Official iRacing data API overview.
- **ACC**
  - [PyAccSharedMemory](https://github.com/rrennoir/PyAccSharedMemory) - Python shared memory reader for ACC. Available on PyPI.
  - [acctelemetry](https://github.com/gotzl/acctelemetry) - Display and analyze MoTeC telemetry data recorded by ACC.
- **F1 Game**
  - [f1-telemetry-client](https://github.com/racehub-io/f1-telemetry-client) - TypeScript UDP client and parser, F1 2018 through F1 23.
  - [Pits n' Giggles](https://github.com/ashwin-nat/pits-n-giggles) - Live telemetry tool for F1 23/24/25 with overlays and dashboards. Python.
- **rFactor 2 / LMU**
  - [TinyPedal](https://github.com/TinyPedal/TinyPedal) - Free open-source telemetry overlay for rFactor 2 and Le Mans Ultimate.
  - [rF2SharedMemoryMapPlugin](https://github.com/TheIronWolfModding/rF2SharedMemoryMapPlugin) - Core shared memory plugin for rF2/LMU.
  - [LMU Trace](https://lmutrace.com/) - Dedicated telemetry analysis web tool for Le Mans Ultimate.
- **GT7**
  - [gt7dashboard](https://github.com/snipem/gt7dashboard) - Live dashboard for GT7 with lap comparison and performance analysis.

## Cross-Series and General Motorsport

- [TheSportsDB](https://www.thesportsdb.com/) - Broad sports API with useful motorsport coverage.
- [Motorsport Stats](https://motorsportstats.com/) - World's largest motorsport data repository with ~3,000 races per season. API via subscription.
- [SportsDataIO Motorsport](https://sportsdata.io/motorsports-api) - Commercial motorsport data across series.
- [Sportradar Racing](https://developer.sportradar.com/racing) - Commercial multi-series racing API.
- [Race Monitor API](https://www.race-monitor.com/Home/API) - Generic race timing API covering grassroots through pro events.
- [List of Formula One Circuits](https://en.wikipedia.org/wiki/List_of_Formula_One_circuits) - Useful seed for circuit metadata.
- [List of Motor Racing Circuits by FIA Grade](https://en.wikipedia.org/wiki/List_of_motor_racing_circuits_by_FIA_grade) - Good source for grade and venue metadata.
- [Motor Sport Magazine Database](https://www.motorsportmagazine.com/database/) - Nearly every motorsport race since 1894. Drivers, teams, circuits, championships.
- [DriverDB](https://www.driverdb.com/) - Career statistics for 70,000+ drivers across all levels of motorsport with Elo-style ranking.
- [FIA Results and Statistics](https://fiaresultsandstatistics.motorsportstats.com/) - Official FIA results portal powered by Motorsport Stats, covering all FIA-sanctioned championships.

## Learning and Education

### Books

- [Wrangling F1 Data With R](https://leanpub.com/wranglingf1datawithr) - Book by Tony Hirst on F1 data manipulation and charting in R.
- [Wrangling F1 Data With Python](https://f1datajunkie.github.io/wranglingf1datawithpython/index.html) - Companion book covering FastF1 demos and Python workflows.

### Blogs and Tutorials

- [F1 Data Junkie](http://www.f1datajunkie.com/) - Tony Hirst's long-running F1 data analysis blog.
- [RaceFans Race Data](https://www.racefans.net/category/race-data/) - Independent analysis articles with race data and statistics.
- [TracingInsights](https://tracinginsights.com/) - Interactive charts for lap times, telemetry, and performance analysis. 2018+ seasons.
- [F1technical.net](https://www.f1technical.net/) - Deep technical articles on aerodynamics, car design, and regulation analysis with active forums.
- [ScarbsF1](https://scarbsf1.wordpress.com/) - Craig Scarborough's long-running F1 technical blog with detailed illustrations and car analysis.
- [Towards Formula 1 Analysis](https://medium.com/towards-formula-1-analysis) - Structured FastF1 tutorials on Medium covering telemetry analysis, race strategy, and minisector comparisons.
- [Motorsport Engineer](https://motorsportengineer.net/) - Courses taught by current and former F1 engineers covering aerodynamics, vehicle dynamics, and CFD.

### YouTube Channels

- [Chain Bear](https://www.youtube.com/@chainbear) - Clear, visual explanations of F1 rules, strategy, and technical concepts.
- [Driver61](https://www.youtube.com/@Driver61) - Racing technique, car setup science, and F1 engineering deep dives.
- [Peter Windsor](https://www.youtube.com/@PeterWindsorF1) - Inside F1 from a veteran journalist with technical depth.
- [Kyle Engineers](https://www.youtube.com/@KyleEngineers) - F1 engineering analysis from a practicing engineer.
- [The Race](https://www.youtube.com/@TheRace) - Largest independent motorsport channel with expert analysis and technical deep dives.
- [CYMotorsport](https://www.youtube.com/@CYMotorsport) - Data-driven F1 driver comparisons, historical analysis, and storytelling.

### Podcasts

- [Beyond the Grid](https://www.youtube.com/@BeyondTheGridF1) - Official F1 podcast with in-depth driver and team principal interviews.
- [Data Driven F1](https://podcasts.apple.com/us/podcast/data-driven-f1/id1527676761) - Technology, data, and behavioral analysis in F1. Biweekly.
- [The Race F1 Podcast](https://the-race.com/podcasts/) - Expert analysis from The Race's F1 journalists.
- [The Race F1 Tech Show](https://podcasts.apple.com/us/podcast/the-race-f1-tech-show/id1502430647) - Former F1 technical director Gary Anderson and Edd Straw discuss car engineering, aerodynamics, and development.

## Films, Documentaries, and Games

### Documentaries

- [Schumacher '94](https://www.imdb.com/title/tt36741795/) (2026) - Netflix. Michael Schumacher's dramatic first championship season in 1994, featuring his wife Corinna and those closest to the seven-time champion.
- [Drive to Survive](https://www.netflix.com/title/80204890) (2019-2026) - Netflix. Behind-the-scenes docuseries covering the drama on and off the F1 grid. 8 seasons.
- [Brawn: The Impossible Formula 1 Story](https://www.imdb.com/title/tt22297946/) (2023) - Disney+. How Brawn GP won the 2009 World Championship as an underfinanced independent team. Narrated by Keanu Reeves. 4 parts.
- [F1: The Academy](https://www.imdb.com/title/tt36711188/) (2025) - Netflix. 15 young women compete in the F1 Academy racing series in pursuit of reaching Formula 1. Produced by Hello Sunshine.
- [The Seat](https://www.imdb.com/title/tt36741795/) (2025) - Netflix. Mercedes' decision to promote 18-year-old Kimi Antonelli to Formula 1 following Lewis Hamilton's departure to Ferrari.
- [Schumacher](https://www.netflix.com/title/81399308) (2021) - Netflix. The life and career of seven-time world champion Michael Schumacher, told through rare interviews and archival footage.
- [A Life of Speed: The Juan Manuel Fangio Story](https://www.netflix.com/title/80208059) (2020) - Netflix. The story of Argentine racing legend Juan Manuel Fangio and his five World Championship titles.
- [Williams](https://www.imdb.com/title/tt5765218/) (2017) - The inspiring story of Sir Frank Williams, the man behind one of the most successful teams in motorsport history.
- [McLaren](https://www.imdb.com/title/tt6209326/) (2017) - The remarkable story of Bruce McLaren, the New Zealander who founded the McLaren Motor Racing team.
- [1](https://www.imdb.com/title/tt2518788/) (2013) - A story of the golden era of Formula 1 racing, when the weights of victory and defeat were measured in human lives.
- [Senna](https://www.imdb.com/title/tt1424432/) (2010) - The story of Ayrton Senna, widely regarded as the greatest F1 driver of all time, charting his physical and spiritual journey on and off the track.

### Films

- [F1](https://www.imdb.com/title/tt16311594/) (2025) - A former driver is brought back into Formula 1 by the owner of a failing team. Starring Brad Pitt. Directed by Joseph Kosinski.
- [Ford v Ferrari](https://www.imdb.com/title/tt1950186/) (2019) - American car designer Carroll Shelby and driver Ken Miles battle corporate interference and the laws of physics to build a car to beat Ferrari at the 1966 Le Mans.
- [Rush](https://www.imdb.com/title/tt1979320/) (2013) - The merciless 1976 rivalry between Formula One rivals James Hunt and Niki Lauda. Directed by Ron Howard.
- [Grand Prix](https://www.imdb.com/title/tt0060472/) (1966) - Drama and romance among Grand Prix drivers on the European racing circuit. Featuring real F1 circuits and drivers of the era.

### Games

- [EA Sports F1 25](https://www.ea.com/games/f1/f1-25) (2025) - Official F1 racing game with career mode, multiplayer, and UDP telemetry output for data tools.
- [F1 Manager 2024](https://store.steampowered.com/app/2287220/F1_Manager_2024/) (2024) - Official F1 management simulation. Strategy, team development, and race management.
- [Gran Turismo 7](https://www.gran-turismo.com/us/gt7/) (2022) - PlayStation racing sim with community-cracked UDP telemetry.
- [Assetto Corsa Competizione](https://www.assettocorsa.it/competizione/) (2019) - Official GT World Challenge sim with shared memory telemetry access.
- [iRacing](https://www.iracing.com/) (2008) - Professional-grade online racing simulation with the most mature data API ecosystem.

## Official Reference Links

### Series

- [Formula 1](https://www.formula1.com/)
- [Formula 2](https://www.fiaformula2.com/)
- [Formula 3](https://www.fiaformula3.com/)
- [Formula E](https://fiaformulae.com/)
- [NASCAR](https://www.nascar.com/)
- [IndyCar](https://www.indycar.com/)
- [FIA WEC](https://www.fiawec.com/)
- [Le Mans](https://www.24h-lemans.com/)
- [IMSA](https://www.imsa.com/)
- [MotoGP](https://www.motogp.com/)
- [WorldSBK](https://www.worldsbk.com/)
- [WRC](https://www.wrc.com/)
- [DTM](https://www.dtm.com/en)

### Governing Bodies and Rules

- [FIA Regulations](https://www.fia.com/regulations)
- [FIA Formula 1 Regulations](https://www.fia.com/regulation/category/29)
- [FIA WEC Regulations](https://www.fiawec.com/en/page/regulations-1)
- [FIM Documents](https://www.fim-moto.com/en/documents)

## Contributing

Contributions welcome! Open a PR with a clear one-line description for each resource. Quality bar:

- **GitHub repos**: 50+ stars
- **Kaggle datasets**: 1,000+ downloads
- **Websites**: actively maintained with recent data
- **YouTube/Podcasts**: established audience, technical depth

## License

This repository is a curated link list. Each linked project keeps its own license and terms of use.
