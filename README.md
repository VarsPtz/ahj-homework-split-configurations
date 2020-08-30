[![Build status](https://ci.appveyor.com/api/projects/status/df8wtdfqdeuvklu5?svg=true)](https://ci.appveyor.com/project/VarsPtz/ahj-homework-split-configurations)
[GitHub Pages](https://varsptz.github.io/ahj-homework-split-configurations/)
### Разделение конфигураций (задача со звёздочкой)

Важно: эта задача не является обязательной

#### Легенда

На данный момент у нас одна конфигурация Webpack: для разработки и для production. В больших проектах конфигурации чаще всего разделяют, в том числе потому, что для production применяются плагины оптимизации, выполнение которых может занять достаточно длительное время.

#### Описание

Следуя инструкциям из лекции, разделите конфигурацию на три части:
* общая
* prod (в prod нужно указать только `mode: 'production'` и настройки оптимизации для плагинов Terser и OptimizeCSSAssets)
* dev

**В качестве результата пришлите проверяющему ссылку на ваш GitHub-проект.**