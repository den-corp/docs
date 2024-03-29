Документ commit rules:

Pull Requests (MR):
    - Если создан MR (Pull Request), который должен быть проверен старшим сотрудником, необходимо установить статус "Ready for review".
    - Назначить исполнителем сотрудника (помимо самого исполнителя задачи), который будет проверять MR(Pull Request).

Структура репозитория:
    - У каждого репозитория проекта есть главная ветка `master`, которая используется как release branch.
    - У каждого репозитория есть старший сотрудник, который принимает все pull requests.

Code review старшим сотрудником:
    - Старший сотрудник проводит code review для каждого pull request.
    - Проверяется соответствие кода стандартам оформления, правильности реализации задачи и отсутствию ошибок.

Работа с репозиторием:
    - Сотрудник должен создать побочную ветку для работы на основе подхода Feature Branch Workflow.
    - Название ветки зависит от задачи, например:
        
        Добавление новых функций:
        feature/<название-функции>
        enhancement/<название-функции>
        new-feature/<название-функции>
        
        Исправление багов:
        bugfix/<описание-бага>
        fix/<описание-бага>
        bug/<описание-бага>
        
        Рефакторинг кода:
        refactor/<описание-рефакторинга>
        code-refactoring/<описание-рефакторинга>
        improvement/<описание-рефакторинга>
        
        Добавление документации:
        docs/<описание-документации>
        documentation/<описание-документации>
        doc/<описание-документации>
        
        Добавление тестов:
        test/<описание-теста>
        testing/<описание-теста>
        test-cases/<описание-теста>
        
        Исправление опечаток и мелких ошибок:
        typo-fix/<описание-опечатки>
        fix-typo/<описание-опечатки>
        typo/<описание-опечатки>
