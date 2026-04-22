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

Understanding the local behavior of the loss function near a minimum is important
both for analyzing neural loss landscapes and for studying how the geometry
of the optimization surface changes with the training set size. Recent Monte Carlo
approaches to loss-landscape convergence rely on Gaussian sampling around a local
minimum, but their performance is highly sensitive to the choice of the sampling scale.
In particular, if the sampling variance is too large, sampled points leave the neighborhood
where the loss is well approximated by its second-order Taylor expansion; if
it is too small, the sampling becomes overly conservative. In this work, we propose
an adaptive rule for selecting the Gaussian sampling scale based on local curvature
information. Using the Hessian at a minimum and a local regularity condition on
the loss landscape, we derive an explicit estimate of the radius of the local quadratic
regime and obtain a closed-form expression for the largest admissible sampling scale
that stays inside this region with prescribed probability. We further validate the
proposed rule experimentally on image classification with ResNet-18 on CIFAR-10.
The results show that the selected scale is well aligned with the region where the
quadratic approximation remains accurate and that the admissible scale decreases
as the dimension of the dominant-curvature subspace increases. Overall, the proposed
method provides a practical geometry-aware calibration of Gaussian sampling
for local loss-landscape analysis and for Monte Carlo estimation of loss-landscape
convergence.



## Citation

If you find our work helpful, please cite us.
```BibTeX
@article{citekey,
    title={Adaptive Selection of the Gaussian Sampling Scale for
Monte Carlo Estimation of Loss-Landscape},
    author={Enikeev Arnold, Nikita Kiselev (consultant), Andrey Grabovoy (advisor)},
    year={2026}
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.
