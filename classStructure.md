statistics 157, earthquake data project
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
  - **A**, Cache Money ( [Repository]() & [S.M.A.R.T Goals]() )
    - Arif Ali                ( [arifyali](https://github.com/arifyali) )
    - David BARRERA           ( [jest4pun](https://github.com/jest4pun) )
    - Kimberly LE             ( [kimberlyle](https://github.com/kimberlyle) )
    - **Wen LIANG**               ( [wliang88](https://github.com/wliang88) )
    - Xiaorui "Sherry" XIA    ( [xsherryxia](https://github.com/xsherryxia) )
  - **B** ( [Repository]() & [S.M.A.R.T Goals]() )
    - Alisha AGRAWAL          ( [alisha791](https://github.com/alisha791) )
    - Theresa ANDRASFAY       ( [tandrasfay](https://github.com/tandrasfay) )
    - **Lorraine HSIAO**          ( [lorrainehsiao](https://github.com/lorrainehsiao) )
    - Jie ZHANG               ( [jzhang980](https://github.com/jzhang980) )
  - **C**, Smile ( [Repository]() & [S.M.A.R.T Goals]() )
    - Timothy HOANG           ( [timothyhoang](https://github.com/timothyhoang) )
    - Reena SHAH              ( [reenashah](https://github.com/reenashah) )
    - Yuqi "Tristan" TAO                ( [tristantao](https://github.com/tristantao) )
    - **David WANG**              ( [davidwang001](https://github.com/davidwang001) )

- Analyzers
  - **1**  ( [Repository]() & [S.M.A.R.T Goals]() )
    - Teresa TENFELDER        ( [teresita](https://github.com/teresita) )
    - Khoa TRAN               ( [kqdtran](https://github.com/kqdtran) )
    - **Roland SHEN**              ( [rolandshen](https://github.com/rolandshen) )
    - Jody ZHANG              ( [j-zhang](https://github.com/j-zhang) )
  - **2** ( [Repository]() & [S.M.A.R.T Goals]() )
    - **Laura CUNNINGHAM**        ( [lauraccunningham](https://github.com/lauraccunningham) )
    - Disi KOA                ( [gnolnait](https://github.com/gnolnait) )
    - John RISKO              ( [johnrisko](https://github.com/johnrisko) )
    - Tay SHIN                ( [taywon](https://github.com/taywon) )
  - **3** ( [Repository]() & [S.M.A.R.T Goals]() )
    - Bonghyun KIM            ( [bonghyun5](https://github.com/bonghyun5) )
    - Yee Tung "Alice" MAN    ( [amx01](https://github.com/amx01) )
    - **Alyssa PARKER**           ( [aparker92](https://github.com/aparker92) )
    - Qi ZHANG                ( [qi-zhang](https://github.com/qi-zhang) )

- Visualizers
  - **#**  ( [Repository]() & [S.M.A.R.T Goals]() )
    - **David LAU**               ( [davidopluslau](https://github.com/davidopluslau) )
    - Ashley SIA              ( [ashleysia](https://github.com/ashleysia) )
    - Raymond MA              ( [raymondma1](https://github.com/raymondma1) )
    - Yoojin JANG             ( [all4ujin](https://github.com/all4ujin) )
  - **$** ( [Repository]() & [S.M.A.R.T Goals]() )
    - **Brian LIOU**              ( [brianliou](https://github.com/brianliou) )
    - Tinghui "Eric" TSAI     ( [wxadqcze](https://github.com/wxadqcze) )
    - Joy CHEN                ( [joyyqchen](https://github.com/joyyqchen) )
    - Sam KIRSCHNER           ( [dr.meow](https://github.com/dr.meow) )
  - **Q, Quakers** ( [Repository]() & [S.M.A.R.T Goals]() )
    - **Carl SHEN**               ( [carlshan](https://github.com/carlshan) )
    - He MA                   ( [sunnymh](https://github.com/sunnymh) )
    - Siyang "Sunny" ZENG     ( [sunnysunnia](https://github.com/sunnysunnia) )
    - Alex CHAO               ( [alexchao56](https://github.com/alexchao56) )
  - **❤** ( [Repository]() & [S.M.A.R.T Goals]() )
    - **Hong SHON**               ( [tzenarr](https://github.com/tzenarr) )
    - Hyung Kyu CHANG         ( [hkchang89](https://github.com/hkchang89) )
    - Sunghoon CHOI           ( [shchoi](https://github.com/schoi) )
    - Christina HO            ( [chocoho](https://github.com/chocoho) )
    - Jinsoo LEE              ( [annyeongjs](https://github.com/annyeongjs) )

- **UNASSIGNED INDIVIDUALS**: Someone please contact them and get them in the loop/working within a group.
    - Vincent CANLAS          ( [vcanlas](https://github.com/vcanlas) )
    - Kuanwei TSENG           ( [kt0009](https://github.com/kt0009) )

**Note**: Presenters will be the group contacts between sub-groups.  These contacts are **bolded** within their respective groups.

Working Diagram
-----
  - Curators:
    - C --> B --> A --> Curator Output
      - C: Scrape USGS Data & Prepare Simple Data Frame
      - B: Cleaning Data and Formating as a `.csv` File
      - A: Translating `.csv` File into a Necessary `.ppx` Format to be Run Through the `ETAS` Package in R, as well as Cleaning Data to exclude Not Applicable (N/A) Values
    - Curator Output Includes Two Files: 
      - A `.csv` File --> _CuratorOutput1_
      - A `.ppx` File --> _CuratorOutput2_
  - Analyzers:
    - Curator Output --> Analyzer Sub-Groups 1, 2, 3
      - 1: Analyzing Curator Output through the MDA Model, Using R --> Outputing Information as _AnalyzerOutput1_
      - 2: Analyzing Curator Output through the ETAS Model, Using R Package `SAPP` and `PtProcess` --> Outputing Information as _AnalyzerOutput2_
      - 3: Analyzing Curator Output through the ETAS Model, Using R Package `SAPP` and `PtProcess` --> Outputing Information as _AnalyzerOutput3_
    - Analyzer Outputs: Output1, Output2, Output3
  - Visualizers
    - Analyzer Outputs (_AnalyzerOutput1_, _AnalyzerOutput2_, _AnalyzerOutput3_) --> Pushed to Specific Visualizer Groups
      - Paths of Analyzer Outputs to Visualizer Groups:
        - _CuratorOutput1_ or _CuratorOutput2_
        - _AnalyzerOutput1_ --> $ 
        - _AnalyzerOutput2_ --> Q
        - _AnalyzerOutput3_ --> ❤

What the Visualizers Will Be Examining & Expected Results
-----
  - #: 
    - Look at the _Curator Output_ as Raw Data & Create a Plot
      - Plot Needs to Include Earthquakes on a World Map with Points Dependent Upon the Individual Earthquake's Magnitude (Size of Point), Depth (Color of Point: Red (Deeper) to Green (Shallower), Adjust Gradient to Clarify the Layering of Earthquake in Close Proximity to One Another)
    - Put Together A Comprehensive Understanding of the Magnitude-Dependent Alarm (MDA) Model
  - $: 
    - Examine & Create a Visual Representation of _AnalyzerOutput1_ --> Create _VisualOutput1_
    - Compare _VisualOutput1_ with _VisualOutput2_
  - Q: 
    - Examine & Create a Visual Representation of _AnalyzerOutput2_ --> Create _VisualOutput2_
    - Put Together A Comprehensive Understanding of the Epidemic-Type Aftershock Sequence (ETAS) Model
    - Examining the ETAS models defined from the R packages `SAPP` & `PtProcess` versus the MDA model.
  - ❤: 
    - Examine & Create a Visual Representation of _AnalyzerOutput3_ --> Create _VisualOutput3_
    - Compare _VisualOutput2_ with _VisualOutput3_

**Note**: To Keep Ourselves in Check, We will be Reappropriating Those involved with the Curator Process with the Checking of Processes & Individuals to Hold Individuals Accountable for Reproducibilty Errors

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
