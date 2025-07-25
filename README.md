<h3 align="center">
  Hi I am Mohamed Abo-Omar
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
</h3>
<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com/?lines=Computer%20Science%20and%20Engineering%20Student;Competitve%20Programmer;Software%20Engineering%20Enthusiast&font=Fira%20Code&center=true&width=600&height=45&color=D27800&vCenter=true&size=22"></a>
</p> 

<h2 align="left">Languages & Tools</h2>
<div align="left">
  <img src="https://api.iconify.design/logos/go.svg" alt="golang" width="45" height="45"/>
<!--   <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="golang" width="40" height="40"/> -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/>
  <img src="https://api.iconify.design/logos/dotnet.svg" alt="dotnet" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="javascript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="html5" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="css" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/jupyter/jupyter-icon.svg" alt="jupyter" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>  
  </div>
  

## Open Source Contributions

### Google Summer of Code

I am a Google Summer of Code 2025 contributor with the **Open Transit Software Foundation (OTSF)**, contributing to **OneBusAway** by developing a Go-based monitoring service to help transit agencies adopt OBA and keep their systems running smoothly.

Here are the contributions I have made so far:


| Repository                                                    | Description                                                                                                                                                                                                         | Type                  | PR / Issue                                                                                                                                                                                                                          | Status                                                                                                                                                                                                  |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [OneBusAway/watchdog](https://github.com/OneBusAway/watchdog) | Added hybrid geo-clustering for unmatched GTFS stops using GTFS hierarchy and S2 cells to expose stable, low-cardinality Prometheus metrics.                                                                        | Feature/Enh.          | [PR #71](https://github.com/OneBusAway/watchdog/pull/71)                                                                                                                                                                            | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Validated GTFS-RT vehicle coordinates using bounding boxes from static GTFS data, reporting out-of-bounds stopped vehicles via Prometheus for improved accuracy and observability.                                  | Docs/Infra<br>        | [PR #73](https://github.com/OneBusAway/watchdog/pull/73)                                                                                                                                                                            | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Tracked GTFS-RT vehicle reporting frequency using Prometheus metrics for total reports and reporting intervals per vehicle.                                                                                         | Feature/Enh<br>       | [PR #70](https://github.com/OneBusAway/watchdog/pull/70)                                                                                                                                                                            | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Exposed unmatched stop locations from GTFS static data as Prometheus metrics and added utilities for mapping stop IDs to coordinates.                                                                               | Feature/Enh<br>       | [PR #69](https://github.com/OneBusAway/watchdog/pull/69)                                                                                                                                                                            | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Added Prometheus metrics for `TripMatchRatio` and `StopMatchRatio` to analyze GTFS-RT and static data alignment across servers and agencies.                                                                        | Feature/Enh<br>       | [PR #68](https://github.com/OneBusAway/watchdog/pull/68)                                                                                                                                                                            | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Added integration testing support for GTFS bundle downloads and OBA API availability with configurable test flags, shared config loading, and updated README instructions.                                          | Test/Infra<br>        | [PR #66](https://github.com/OneBusAway/watchdog/pull/66),[PR #67](https://github.com/OneBusAway/watchdog/pull/67)<br>                                                                                                               | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Updated healthcheck endpoint to return detailed JSON response with status, environment, version, servers, and readiness info.                                                                                       | Feature/Enh<br>       | [PR #65](https://github.com/OneBusAway/watchdog/pull/65)<br><br>                                                                                                                                                                    | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Integrated structured Sentry error reporting across the application with scoped context, unified helper options, middleware wrapping, and enhanced metrics error tracking for improved observability and debugging. | Observability/Enh<br> | [PR #63](https://github.com/OneBusAway/watchdog/pull/63),[PR #62](https://github.com/OneBusAway/watchdog/pull/62),[PR #61](https://github.com/OneBusAway/watchdog/pull/61),[PR #60](https://github.com/OneBusAway/watchdog/pull/60) | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Unified error reporting and GTFS data handling by refactoring Sentry usage with consistent options and centralizing GTFS parsing and real-time feed fetching across application layers.                             | Refactor/Infra<br>    | [PR #64](https://github.com/OneBusAway/watchdog/pull/64),[PR #72](https://github.com/OneBusAway/watchdog/pull/72)                                                                                                                   | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                             | Improved configuration and Docker usage documentation by renaming `config.json` to `config.json.template`, updating `.gitignore,` and enhancing README with clear setup instructions and usage examples.            | Refactor/Infra<br>    | [PR #59](https://github.com/OneBusAway/watchdog/pull/59)                                                                                                                                                                            | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |




### Continued OSS Work
- **[Open Transit Software Foundation - OneBusAway](https://github.com/OneBusAway)**
  -  [OneBusAway-Application-Modules](https://github.com/OneBusAway/onebusaway-application-modules):
Extended the Java-based Metrics API with new metrics to support the standalone Watchdog service.

  - [Watchdog](https://github.com/OneBusAway/watchdog):
Improved Go-based backend testing by refactoring core logic and relocating unit tests to enhance modularity and raise test coverage to 74%.

- **[Invesalius3](https://github.com/invesalius/invesalius3)**: Implemented a base solution for progress bar functionality and applied it to the File/Save operation.

### Contribution List



| Repository                                                                                     | Description                                                                                                                                                            | Type                  | PR / Issue                                                                                                                                                                             | Status                                                                                                                                                                                                  |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[InVesalius3](https://github.com/invesalius/invesalius3)**                                   | Implemented a reusable progress bar for file operations in InVesalius, enhancing Save Project functionality with real-time updates using Python, wxPython, and PubSub. | GUI/Enh.              | [PR #735](https://github.com/invesalius/invesalius3/pull/735), [Issue #707](https://github.com/invesalius/invesalius3/issues/707)                                                      | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| [OneBusAway-Application-Modules](https://github.com/OneBusAway/onebusaway-application-modules) | Implemented per-agency matched trip count in the Metrics API using Java.                                                                                               | Feature/Enh.          | [PR #415](https://github.com/OneBusAway/onebusaway-application-modules/pull/415), [Issue #401](https://github.com/OneBusAway/onebusaway-application-modules/issues/401)                | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                                                              | Added total real-time records metric per agency in the Metrics API using Java.                                                                                         | Feature/Enh.          | [PR #421](https://github.com/OneBusAway/onebusaway-application-modules/pull/421), [Issue #400](https://github.com/OneBusAway/onebusaway-application-modules/issues/400)                | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| [OneBusAway/watchdog](https://github.com/OneBusAway/watchdog)                                  | Migrated and added unit tests using Go to improve metrics package coverage.                                                                                            | Test/Enh.             | [PR #46](https://github.com/OneBusAway/watchdog/pull/46), [Issue #45](https://github.com/OneBusAway/watchdog/issues/45), [Issue #47](https://github.com/OneBusAway/watchdog/issues/47) | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |
| ↳                                                                                              | Refactored main logic into testable helpers using Go and added unit tests.                                                                                             | Refactor+Test/Enh<br> | [PR #53](https://github.com/OneBusAway/watchdog/pull/53), [Issue #45](https://github.com/OneBusAway/watchdog/issues/45)                                                                | ![Merged](https://camo.githubusercontent.com/198470a4c39007f3a895083626b44e38c683e73841a855946ea5c10fe4b744a3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d65726765642d383935376535)<br> |

---

## Projects

- **[Gitlet](https://github.com/Abo-Omar-74/gitlet)**: Built a Java-based distributed version control system implementing core Git functionalities with persistence and data integrity.
- **[httpServe](https://github.com/Abo-Omar-74/httpServer)**: Built an HTTP server in Go, incorporating custom APIs, middleware, and database integration using the standard library.
- **[Automotive E-commerce Platform](https://github.com/Abo-Omar-74/AutomotiveEcommercePlatform)**: Created a full-featured ASP.NET website for automotive product shopping, trader management, and car inventory handling.
- **[Pathfinding Algorithm Visualizer](https://github.com/Abo-Omar-74/Pathfinding-Algorithm-Visualizer)**: Developed a JavaScript tool for visualizing BFS, DFS, and Dijkstra's algorithms.


<h2 align="left">Competitive Programming Profiles</h2>
<div align="left">
    <a href="https://codeforces.com/profile/Abo-Omar" target="blank">
        <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg" alt="https://codeforces.com/profile/Abo-Omar" height="40" width="40" />
    </a>
    &emsp; 
    <a href="https://leetcode.com/u/Abo-Omar/" target="blank">
        <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="https://leetcode.com/u/Abo-Omar/" height="35" width="30" />
    </a>
</div>

<h2 align="left">Contact Me</h2>
<div align="left">
  <a href="https://www.linkedin.com/in/mohamed-abo-omar/" target="_blank">
    <img src="https://img.shields.io/badge/Linkedin-0b66c3?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:mohamedaboomar1211@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-e34033?style=flat&logo=Gmail&logoColor=white"/>
  </a>
</div>
