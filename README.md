# Title

<!-- Change `kisnikser/m1p-template` to `intsystems/your-repository`-->
[![License](https://badgen.net/github/license/kisnikser/m1p-template?color=green)](https://github.com/kisnikser/m1p-template/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/kisnikser/m1p-template)](https://github.com/kisnikser/m1p-template/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/kisnikser/m1p-template.svg?color=0088ff)](https://github.com/kisnikser/m1p-template/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/kisnikser/m1p-template.svg?color=7f29d6)](https://github.com/kisnikser/m1p-template/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Enikeev Arnold </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Nikita Kiselev, PhD/DSc </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Andrey Grabovoy, PhD/DSc </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper/main.pdf)
- [Slides](slides/main.pdf)

## Abstract

Поведение функции потерь возле минимума является важной задачей для оптимального обучения нейросетей. Задача поиска достаточного размера обучающей выборки является открытой и для анализа зависимости модели от размера выборки необходимо знать локальные свойства оптимизационной поверхности. Распределенный подход к оценке сходимости поверхности функции потерь использует Monte Carlo сэмплирование из гауссовского распределения в окрестности локального минимума. 
Целью исследования - разработать адаптивные методы выбора параметров распределения сэмплирования на основе свойств Гессиана функции потерь и провести сравнительный анализ различных стратегий выбора. Для этого рассматриваются зависимость оценки сходимости от дисперсии для различных архитектур и предлагается метод выбора параметра на основе собственных значений гессиана функции. Различные стратегии выбора сравниваются на задаче классификации изображений.
Ранее не исследовались адаптивные методы выбора параметров распределения сэмплирования. Развитие исследований в этом направлении позволит сделать распределенный подход более практичным и устойчивым.
Результаты могут быть полезны для анализа оптимальной обучающей выборки в задаче обучения нейросетей.


## Citation

If you find our work helpful, please cite us.
```BibTeX
@article{citekey,
    title={Title},
    author={Enikeev Arnold, Nikita Kiselev (consultant), Andrey Grabovoy (advisor)},
    year={2025}
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.
