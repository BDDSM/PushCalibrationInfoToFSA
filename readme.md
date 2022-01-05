# Инструменты для передачи результатов поверки в ФСА

[![GitHub release](https://img.shields.io/github/v/release/csm-ivanovo-ru/PushCalibrationInfoToFSA.svg?sort=semver&logo=github)](https://github.com/csm-ivanovo-ru/PushCalibrationInfoToFSA/releases)

[![Semantic Versioning](https://img.shields.io/static/v1?label=Semantic%20Versioning&message=v2.0.0&color=green&logo=semver)](https://semver.org/lang/ru/spec/v2.0.0.html)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-v1.0.0-yellow.svg?logo=git)](https://conventionalcommits.org)

Данный репозиторий содержит инструменты для передачи результатов поверки в
ФСА (Федеральная служба по аккредитации - Росаккредитация)
в соответствии с действующим законодательством,
а также сопутствующие инструкции.

## Подготовка среды

Для внесения изменений в пакет и повторной сборки проекта потребуются следующие продукты:

Под Windows:

- [Git][]
- текстовый редактор, настоятельно рекомендую [VSCode][]
- [GitVersion][]

Для [VSCode][] рекомендую установить расширения, указанные в рабочей области.

Далее следует скопировать исходные файлы проекта, клонировав git репозиторий.
Для сборки документов используется [GitVersion][], а он требует наличия именно
репозитория со всей историей.

## Внесение изменений

Репозиторий проекта размещён по адресу
[github.com/csm-ivanovo-ru/PushCalibrationInfoToFSA](https://github.com/csm-ivanovo-ru/PushCalibrationInfoToFSA).
Стратегия ветвления - Git Flow.

При необходимости внесения изменений в сам проект предложите Pull Request в основной
репозиторий в ветку `develop`.

[Git]: https://github.com/git-guides/install-git#install-git-on-windows "Install Git on Windows"
[VSCode]: https://code.visualstudio.com/ "Visual Studio Code"
[PowerShellCore]: https://github.com/PowerShell/PowerShell "PowerShell Core"
[GitVersion]: https://github.com/GitTools/GitVersion "Easy Semantic Versioning for projects using Git"
