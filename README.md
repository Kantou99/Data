gantt
    %% --------------------------------------------------------------
    %%  MILESTONES GANTT CHART
    %%  "Week 1" mapped to 2025-01-05. Adjust dates as needed.
    %%  Enjoy a bright, color-coded timeline!
    %% --------------------------------------------------------------

    title Moral Optimization Gantt Chart (Weeks 1-40)
    dateFormat YYYY-MM-DD
    axisFormat %b %d  %% e.g., "Jan 05"

    section Thesis Timeline
    Project Scoping           :scoping,    2025-01-05, 2025-01-11
    DA Selection              :da,         2025-01-12, 2025-01-18
    Proposal Development      :proposal,   2025-01-19, 2025-02-23
    Ethical Approval          :ethics,     2025-02-24, 2025-03-16
    Specification & Design    :spec,       2025-03-17, 2025-04-20
    System Development        :system,     2025-03-17, 2025-06-09
    Data Collection           :data,       2025-03-17, 2025-04-27
    System Testing            :testing,    2025-06-16, 2025-07-13
    Research Paper Draft      :draft,      2025-07-14, 2025-08-11
    Final Submission          :final,      2025-09-08, 2025-09-29

    %% --------------------------------------------------------------
    %% CLASS DEFINITIONS (Color & Style)
    %% Feel free to tweak colors (fill/stroke) or text color.
    %% --------------------------------------------------------------
    classDef scoping fill:#7fdbff,   stroke:#0f375e, stroke-width:2px, color:#000
    classDef da      fill:#ffd700,   stroke:#b29500, stroke-width:2px, color:#000
    classDef proposal fill:#2ecc40,  stroke:#17912b, stroke-width:2px, color:#000
    classDef ethics  fill:#ff4136,   stroke:#c30007, stroke-width:2px, color:#fff
    classDef spec    fill:#0074d9,   stroke:#00549f, stroke-width:2px, color:#fff
    classDef system  fill:#39cccc,   stroke:#278c8c, stroke-width:2px, color:#000
    classDef data    fill:#b10dc9,   stroke:#7e0b8f, stroke-width:2px, color:#fff
    classDef testing fill:#85144b,   stroke:#580f34, stroke-width:2px, color:#fff
    classDef draft   fill:#aaaaaa,   stroke:#888888, stroke-width:2px, color:#000
    classDef final   fill:#111111,   stroke:#444444, stroke-width:2px, color:#fff

    %% --------------------------------------------------------------
    %% APPLY CLASSES TO EACH TASK
    %% --------------------------------------------------------------
    class scoping    scoping
    class da         da
    class proposal   proposal
    class ethics     ethics
    class spec       spec
    class system     system
    class data       data
    class testing    testing
    class draft      draft
    class final      final
