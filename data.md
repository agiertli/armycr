version: 3
domain: Armáda Českej Republiky
created_by: agiertli
seed_examples:
  - context: |
      Detailní popis protivzdušné obrany armády ČR
    questions_and_answers:
      - question: |
          Jakou protivzdušnou obranu vlastní armáda ČR?
        answer: |
          2K12 Kub, SPYDER, RBS-70
      - question: |
          Jaká je nejpoužívanější  protivzdušná obrana  Armády ČR?
        answer: |
          RBS-70 a RBS-70 NG
      - question: |
          Z jakých zemí pocházejí české vojenské letadla?
        answer: |
          Švédsko, Izrael, ZSSR
  - context: |
      Seznam vojenských letadel ve vlastnictví armády ČR
    questions_and_answers:
      - question: |
          Jaké vojenská letadla vlastní Armáda ČR?
        answer: |
          Saab JAS-39 Gripen - stíhací letoun, Lockheed Martin F-35 Lightning II - stíhací letoun, Aero L-159 ALCA - lehký bojový letoun
      - question: |
          Jaký jsou nejpoužívanější  vojenské letadla  Armády ČR?
        answer: |
          Aero L-159 ALCA - 16ks
      - question: |
          Z jakých zemí pocházejí české vojenské letadla?
        answer: |
          Švédsko, Česko, USA
  - context: |
      Česká armáda vlastní obrněná vozidla
    questions_and_answers:
      - question: |
          Jaké obrněná vozidla vlastní Armáda ČR?
        answer: |
          BVP-1, BVP-2,Pandur II
      - question: |
          Jaký jsou nejpoužívanější  obrněná vozidla  Armády ČR?
        answer: |
          BVP-2
      - question: |
          Z jakých zemí pocházejí české speciální tank?
        answer: |
          BVP-2 - Československo, CV90 - Švédsko, BVP-1 - Československo, Pandur II - Česko, Rakúsko
  - context: |
      Česká armáda rovněž vlastní i tzv. speciální tanky
    questions_and_answers:
      - question: |
          Jaké speciální tanky vlastní Armáda ČR?
        answer: |
          MT-55A, SPOT-55, VT-55A
      - question: |
          Jaký je nejpoužívanější speciální tank Armády ČR?
        answer: |
          MT-55A
      - question: |
          Z jakých zemí pocházejí české speciální tank?
        answer: |
          ZSSR, Česko, Nemecko
  - context: |
      | **Typ**      | **Počet**     | **Púvod** |
      |----------------|--------------|-------------|
      | T-72M4 CZ      | 30           | Česko       |
      | Leopard 2      | 42           | Nemecko     |
      | T-72M1         | 19           | ZSSR        |
    questions_and_answers:
      - question: |
          Jaké tanky má Armáda ČR k dispozici?
        answer: |
          T-72M4 CZ - 30ks, puvod ČR. Leopard 2 - 42ks, puvod Nemecko. T-72M1  - 19ks, puvod ZSSR.
      - question: |
          Jaký je nejpoužívanější tank Armády ČR?
        answer: |
          Leopard 2
      - question: |
          Z jakých zemí pocházejí české tanky?
        answer: |
          Česko, Nemecko, ZSSR
document_outline: |
  Seznam tanků, které má armáda ČR k dispozici
document:
  repo: https://github.com/agiertli/armycr
  commit: e2d2510288ec0aaeb10947e8c7aa222331bf7b80
  patterns:
    - data.md
