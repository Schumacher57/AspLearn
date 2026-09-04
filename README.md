# AspLearn

Учебный проект по ASP.NET Core из курса Кирилла Сачкова ".NET Fullstack Development".

Сейчас решение содержит API `PetFamily.API` — основу для практики разработки серверных приложений на C#.

## Стек

- C# и ASP.NET Core
- .NET 10
- OpenAPI

## Структура

```text
AspLearn.slnx
backend/
  src/
    PetFamily.API/    # ASP.NET Core Web API
```

## Требования

- .NET SDK 10.0 или новее

Проверить установленную версию SDK:

```bash
dotnet --version
```

## Запуск

Из корня репозитория:

```bash
dotnet run --project backend/src/PetFamily.API
```

После запуска API выводит адреса, на которых доступно приложение. В режиме разработки OpenAPI-документ доступен по адресу `/openapi/v1.json`.

## Проверка сборки

```bash
dotnet build AspLearn.slnx
```

## Материалы курса

Конспекты и план обучения находятся в отдельном каталоге `CSharpKirillSachkov` на локальном компьютере. В этот репозиторий добавляется только практическая часть — исходный код проекта.
