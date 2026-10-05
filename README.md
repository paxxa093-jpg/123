# TsunamiTornado — Minecraft 1.16.5

Плагин под Paper/Spigot API 1.16.5.

## Сборка

Требуется Java 8 и Maven.

```text
mvn clean package
```

Готовый JAR появится в:

`target/TsunamiTornado-1.0.0.jar`

## Команды

```text
/tsunami <1-50> [скорость 1-100] [сила 0-100]
/tornado <F1-F5|EleronoTornado> [скорость 1-100]
/disaster stop
```

Примеры:

```text
/tsunami 1 20 0
/tsunami 25 50 20
/tsunami 50 100 100

/tornado F1 20
/tornado F3 60
/tornado F5 100
/tornado EleronoTornado 100
```

## Важно

Это намеренно сделано через Bukkit/Paper API и ограниченный бюджет обработки блоков за тик.
EleronoTornado и tsunami 50/100 могут создавать очень большую нагрузку на сервер.
Перед запуском на основном мире сделай резервную копию.

Документация API 1.16.5:
https://jd.papermc.io/paper/1.16.5/
