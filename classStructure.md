presentation
=====

Goals
-----
  - Class Goal
    - To produce an earthquake alarm error optimization model that more accurately predicts BG Luen's model through comparisons between the accuracy of three models: the Epidemic-Type Aftershock Sequence (ETAS), Poisson, and Magnitude-Dependent Automatic Alarm (MDA).
  - Horizontal Goals
    - _Curator_
      - To scrape, clean, and present a data frame with information from the USGS Earthquake monitoring system updating in realtime.
    - _Analyzer_
      - To compare multiple methods of understanding earthquake data utilizing the Curator's data frame in the form of a `.ppx` file.
      - To understand ETAS: Through R, analyze the Curator's data with three (3) downloadable packages: `ETAS`, `SAPP`, & `PtProcess`.
      - To understand MDA: Utilize R's functions in explaining the model alarm system.
    - _Visualizer_
      - Using the Analyzers' outputs, visualize the multiple methods and understand through comparison if there is a more accurate indicator of earthquake alarms.
      - Understand the models more accurately to develop a clear mathematical understanding of the models, parameters, and produced outputs.  

Horizontal Sub-Groups
-----
- Curators
  - A, Cache Money
    - Arif Ali                ( [arifyali](https://github.com/arifyali) )
    - David BARRERA           ( [jest4pun](https://github.com/jest4pun) )
    - Kimberly LE             ( [kimberlyle](https://github.com/kimberlyle) )
    - **Wen LIANG**               ( [wliang88](https://github.com/wliang88) )
    - Xiaorui "Sherry" XIA    ( [xsherryxia](https://github.com/xsherryxia) )
  - B
    - Alisha AGRAWAL          ( [alisha791](https://github.com/alisha791) )
    - Theresa ANDRASFAY       ( [tandrasfay](https://github.com/tandrasfay) )
    - **Lorraine HSIAO**          ( [lorrainehsiao](https://github.com/lorrainehsiao) )
    - Jie ZHANG               ( [jzhang980](https://github.com/jzhang980) )
  - C, Smile
    - Timothy HOANG           ( [timothyhoang](https://github.com/timothyhoang) )
    - Reena SHAH              ( [reenashah](https://github.com/reenashah) )
    - Yuqi "Tristan" TAO                ( [tristantao](https://github.com/tristantao) )
    - **David WANG**              ( [davidwang001](https://github.com/davidwang001) )

- Analyzers
  - 1 
    - Teresa TENFELDER        ( [teresita](https://github.com/teresita) )
    - Khoa TRAN               ( [kqdtran](https://github.com/kqdtran) )
    - **Roland SHEN**              ( [rolandshen](https://github.com/rolandshen) )
    - Jody ZHANG              ( [j-zhang](https://github.com/j-zhang) )
  - 2
    - **Laura CUNNINGHAM**        ( [lauraccunningham](https://github.com/lauraccunningham) )
    - Disi KOA                ( [gnolnait](https://github.com/gnolnait) )
    - John RISKO              ( [johnrisko](https://github.com/johnrisko) )
    - Tay SHIN                ( [taywon](https://github.com/taywon) )
  - 3
    - Bonghyun KIM            ( [bonghyun5](https://github.com/bonghyun5) )
    - Yee Tung "Alice" MAN    ( [amx01](https://github.com/amx01) )
    - **Alyssa PARKER**           ( [aparker92](https://github.com/aparker92) )
    - Qi ZHANG                ( [qi-zhang](https://github.com/qi-zhang) )

- Visualizers
  - # 
    - **David LAU**               ( [davidopluslau](https://github.com/davidopluslau) )
    - Ashley SIA              ( [ashleysia](https://github.com/ashleysia) )
    - Raymond MA              ( [raymondma1](https://github.com/raymondma1) )
    - Yoojin JANG             ( [all4ujin](https://github.com/all4ujin) )
  - $
    - **Brian LIOU**              ( [brianliou](https://github.com/brianliou) )
    - Tinghui "Eric" TSAI     ( [wxadqcze](https://github.com/wxadqcze) )
    - Joy CHEN                ( [joyyqchen](https://github.com/joyyqchen) )
    - Sam KIRSCHNER           ( [dr.meow](https://github.com/dr.meow) )
  - Q, Quakers
    - **Carl SHEN**               ( [carlshan](https://github.com/carlshan) )
    - He MA                   ( [sunnymh](https://github.com/sunnymh) )
    - Siyang "Sunny" ZENG     ( [sunnysunnia](https://github.com/sunnysunnia) )
    - Alex CHAO               ( [alexchao56](https://github.com/alexchao56) )
  - ❤
    - **Hong SHON**               ( [tzenarr](https://github.com/tzenarr) )
    - Hyung Kyu CHANG         ( [hkchang89](https://github.com/hkchang89) )
    - Sunghoon CHOI           ( [shchoi](https://github.com/schoi) )
    - Christina HO            ( [chocoho](https://github.com/chocoho) )
    - Jinsoo LEE              ( [annyeongjs](https://github.com/annyeongjs) )

- **UNASSIGNED INDIVIDUALS**
    - Vincent CANLAS          ( [vcanlas](https://github.com/vcanlas) )
    - Kuanwei TSENG           ( [kt0009](https://github.com/kt0009) )

**Note**: Presenters will be the group contacts between sub-groups.  These contacts are **bolded** within their respective groups.

Working Diagram
-----
  - C3 --> C2 --> C1 --> Curator Output
    - Curators:
      - Scrape USGS Data
      - Export as a `.csv` File
      - Clean `.csv` File
      - Translate `.csv` File as a Necessary `.ppx` File: Curator Output
  - Curator Output --> Push to Analyzers
    - Analyzers:
      - Curator Output --> A1: Analyze MDA Model --> A1
      - Curator Output --> A2: Analyze ETAS Model, R `SAPP` & `PtProcess` Packages --> A2
      - Curator Output --> A3: Analyze ETAS Model, R `SAPP` & `PtProcess` Packages --> A3
  - Analyzer Outputs (A1, A2, A3) --> Push to Visualizers
    - Visualizers
      - A1 --> # & Q & ❤
      - A2 --> $ & Q & ❤
      - A3 --> # & $ & ❤

  - Work Flow
    - Curators: 
      - C --> B --> A -->   
    - Analyzers:
      - A1
        - --> 1 --> ❤
        - --> 1 --> #
      - A2
        - --> 2 --> ❤
        - --> 2 --> Q
        - --> 2 --> $
      - A3
        - --> 3 --> ❤
        - --> 3 --> $
        - --> 3 --> #
    - Visualizers 

What the Visualizers Will Be Examining
-----
  - #: Examing the ETAS model defined from the R package `ETAS` versus the MDA model.
  - $: Examing the ETAS models defined from the R packages `ETAS` versus `SAPP` & `PtProcess`.
  - Q: Examining the ETAS models defined from the R packages `SAPP` & `PtProcess` versus the MDA model.
  - ❤: Gathering data from _all_ three (3) Analyzer groups, they will be looking at the ETAS models evaluated upon R's packages `ETAS`, `SAPP`, & `PtProcess` and a developed MDA.

S.M.A.R.T. Goals
-----
  - Specific
  - Measurable
  - Attainable
  - Relevant
  - Time-Bound

**S.M.A.R.T._E_._R_. Goals**
  - Evaluate
  - Re-Evaluate
