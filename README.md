# Robert Amartisoaei

I'm a System Test Technician. For four years I've validated telecom hardware at Flex (Nokia project) and traced failures back to their root cause. Software is what I build on the side: Android apps first, web apps too, and anything else worth learning.

I build TrueRide with AI coding agents. I also set up and maintain the agent configuration on my own Linux machine (hooks, rules, review agents, memory), so the tooling is part of the work, not a black box.

## First project: TrueRide

TrueRide is an Android app for ride-hailing drivers. It reads the ride offer on screen with on-device OCR (Google ML Kit) and shows earnings per hour and per kilometre, the estimated car cost and the profit before the driver decides. The app never accepts or declines a ride.

- The core modules (model, calculation, parsing) are plain Kotlin/JVM, and the build fails if they import Android.
- Money is computed with BigDecimal. Parsing rules live as versioned data, separate from the calculation engine.
- About 545 test files, plus an automated regression run against recorded fixtures.

Repository coming soon.

## How I work with AI

I write the spec and make the design decisions. AI coding agents write most of the code. I review every change against the tests and a decision log, so each choice has a written reason.

## Data and ML

These are my data analytics capstone projects. I did them by hand, without AI coding tools: the analysis, the SQL and R code and the conclusions. TrueRide is the only project here built with AI coding agents.

| Project | What it does | Stack |
|---|---|---|
| [Eating disorder risk factors](https://github.com/Ro98ert/Neurobehavioral-Factors-in-Eating-Disorders-Study) | Logistic regression on survey data from 550 students | R |
| [Social media usage](https://github.com/Ro98ert/Social-Media-User-Analysis) | Usage, stress and sleep patterns in a synthetic dataset | BigQuery SQL, Tableau |
| [Bellabeat](https://github.com/Ro98ert/Bellabeat-Case-Study) | Fitbit activity and sleep analysis for a wellness brand | SQL, R |
| [Cyclistic](https://github.com/Ro98ert/Cyclistic-Case-Study) | Five quarters of bike-share trips, casual riders vs members | SQL, R |

## Skills

| Area | Tools |
|---|---|
| Android | Kotlin, Jetpack Compose, Gradle, ML Kit |
| Data | SQL (Postgres, BigQuery), R, Tableau |
| AI tooling | Claude Code, agent hooks and rules, MCP servers |
| Testing | Telecom hardware validation, root-cause analysis, test-first development |
| Way of working | Git, Docker, Linux |

## Certifications

![Google Data Analytics](https://img.shields.io/badge/Google-Data%20Analytics-4285F4?style=flat&logo=google&logoColor=white)
![Google AI](https://img.shields.io/badge/Google-AI%20Essentials-4285F4?style=flat&logo=google&logoColor=white)

## Contact & Links

- **Location:** Timișoara, Romania
- **Email:** robert.amartisoaei.98@gmail.com
- **LinkedIn:** [Robert Amartisoaei](https://www.linkedin.com/in/robert-a-lnkdn98)
- **Resume:** [PDF](https://drive.google.com/file/d/1Nwg1zYfi8rexGNrt9BC1EH788LnKrub4/view?usp=drive_link)
