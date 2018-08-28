### Езици от ниско и високо ниво, среди за изпълнение (Runtime Environments)

Програмата в своята същност е **набор от инструкции**, които карат компютъра да свърши определена задача. Те се въвеждат от програмиста и се **изпълняват безусловно от машината**.

Съществуват различни видове **езици за програмиране**. С езиците от най-ниско ниво могат да бъдат написани **самите инструкции**, които **управляват процесора**, например с езика "**assembler**". С езици от малко по-високо ниво като **C** и **C++** могат да бъдат създадени операционна система, драйвери за управление на хардуера (например драйвер за видеокарта), уеб браузъри, компилатори, двигатели за графика и игри (game engines) и други системни компоненти и програми. С езици от още по-високо ниво като **C#**, **Python** и **JavaScript** се създават приложни програми, например програма за четене на поща или чат програма.

**Езиците от ниско ниво** управляват директно хардуера и изискват много усилия и огромен брой команди, за да свършат единица работа. **Езиците от по-високо ниво** изискват по-малко код за единица работа, но нямат директен достъп до хардуера. На тях се разработва приложен софтуер, например уеб приложения и мобилни приложения.

Болшинството софтуер, който използваме ежедневно, като музикален плеър, видеоплеър, GPS програма и т.н., се пише на **езици за приложно програмиране**, които са от високо ниво, като C#, Java, Python, C++, JavaScript, PHP и др.

**C# е компилируем език**, а това означава, че пишем команди, които се компилират преди да се изпълнят. Именно тези команди, чрез помощна програма (компилатор), се преобразуват във файл, който може да се изпълнява (executable). За да пишем на език като **C#** ни трябва текстов редактор или среда за разработка и **.NET среда за изпълнение**.

**.NET средата за изпълнение** (.NET Runtime Environment) представлява виртуална машина, нещо като компютър в компютъра, която може да изпълнява компилиран C# код. С риск да навлезем в твърде много детайли, трябва да поясним, че езикът C# се компилира до междинен .NET код и се изпълнява от .NET средата, която компилира този междинен код допълнително в движение до машинни инструкции (машинен код) за да се изпълни от микропроцесора. .NET средата съдържа библиотеки с класове, **CSC** компилатор, **CLR** (Common Language Runtime - CLR) и други компоненти, които са необходими, за да работим с езика C# и изпълняваме C# програми.

**Средата .NET** е достъпна като свободен софтуер с отворен код за всички съвременни операционни системи (като Windows, Linux и Mac OS X). Тя има две разновидности, **.NET Framework** (по-старата) и **.NET Core** (по-новата), но всичко това няма съществено значение за навлизането в програмирането. Нека се фокусираме върху писането на програми с езика C#.