# Лекция 1. Жизненный цикл ПО

1. [Software crisis](https://en.wikipedia.org/wiki/Software_crisis)
2. [Systems development life cycle](https://en.wikipedia.org/wiki/Systems_development_life_cycle): разработка требований, анализ, проектирование, разработка, тестирование, внедрение, эксплуатация, вывод из эксплуатации
   * [ISO/IEC/IEEE 12207 Systems and software engineering – Software life cycle processes](https://en.wikipedia.org/wiki/ISO/IEC_12207)
4. Модели жизненного цикла программного обеспечения ([статья на Хабре](https://habr.com/ru/post/111674/))
   * последовательная - все требования определены, один этап
   * инкрементная - все требования определены, несколько этапов
   * эволюционная - не все требования определены, несколько этапов
   * формальных преобразований
5. Последовательные методы разработки
   * [водопадная (каскадная) модель](https://en.wikipedia.org/wiki/Waterfall_model)
     * system requirements
     * software requirements
     * analysis
     * program design
     * coding
     * testing
     * operations
   * методология Ройса (W.Royce Managing the development of larger software systems) - улучшенная каскадная
     * preliminary program design before analysis and coding
     * documentation (requirements, design specs, test plan, operating instructions)
     * *do it twice* (roots of prototyping?)
     * testing must be planned, controlled and monitored 
     * multiple sofware reviews by the customer
   * [V-chart model by J.Munson, B.Boehm](https://en.wikipedia.org/wiki/V-Model)
     * > The left side of the "V" represents the decomposition of requirements, and creation of system specifications. The right side of the "V" represents integration of parts and their validation and verification (validation - "are you building the right thing?", verification - "are you building it right?").
6. Методы дальнейшей декомпозиции жизненого цикла:
   * Многопроходная модель (Incremental model)
   * Модель прототипирования (80-е) - фактически эволюционная
   * [Spiral model by B.Boehem](https://en.wikipedia.org/wiki/Spiral_model): (анализ рисков + прототипирование)* detailed design, coding, testing
7. Быстрая разработка приложений. CASE-системы (~90-е)
   * [Rapid application development by J.Martin](https://en.wikipedia.org/wiki/Rapid_application_development)
   * [Computer-Aided Software Engineering](https://en.wikipedia.org/wiki/Computer-aided_software_engineering)