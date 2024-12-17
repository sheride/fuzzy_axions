# Fuzzy Axions and Associated Relics

This repository stores the data for some of the example models of fuzzy dark matter in type IIB string theory obtained in [ArXiv:2412.12012](https://arxiv.org/abs/2412.12012). It also contains a Python notebook to illustrate the manipulation of these models in `CYTools`.

## Summary of results

In [ArXiv:2412.12012](https://arxiv.org/abs/2412.12012), we study fuzzy axion dark matter in type IIB string theory, for axions descending from the Ramond-Ramond four-form in compactifications on orientifolds of Calabi-Yau hypersurfaces. Such models can be tested by cosmological measurements if a significant relic abundance of fuzzy dark matter arises, which we argue is most common in models with small numbers of axions. We construct a topologically exhaustive ensemble of more than 350,000 Calabi-Yau compactifications yielding up to seven axions, and in this setting we perform a systematic analysis of misalignment production of fuzzy dark matter. This repository stores the ensemble of models constructed in our search.

<br>

<p align="center">
  <img src="/images/string_flowchart.png" width="450">
</p>

<br>

<p align="center">
  <img src="/images/cosmo_flowchart.png" width="450">
</p>

<br>

<br>


## Working with this repository

To get started, we recommend using the notebook [`notebook.ipynb`](/notebook.ipynb), which reads in data from a `pickle`d `pandas` DataFrame saved as [`data.p`](./data.p/). The notebook provides a brief demo on how to use our data to interface with [CYTools](https://cy.tools) and to reproduce some properties of our models.

> [!IMPORTANT]
> The code makes use of basic functions from [CYTools](https://cy.tools). For help with the installation, please check out the [documentation](https://cy.tools/docs/getting-started/) or reach out to us.

## Contact 

For questions or feedback, please get in touch: <es888@cornell.edu> or <as3475@cornell.edu>.


## Reference

If you use this database for future publications, please cite

```
@article{Sheridan:2024vtt,
    author = "Sheridan, Elijah and Carta, Federico and Gendler, Naomi and Jain, Mudit and Marsh, David J. E. and McAllister, Liam and Righi, Nicole and Rogers, Keir K. and Schachner, Andreas",
    title = "{Fuzzy Axions and Associated Relics}",
    eprint = "2412.12012",
    archivePrefix = "arXiv",
    primaryClass = "hep-th",
    reportNumber = "KCL-PH-TH/2024-75",
    month = "12",
    year = "2024"
}
```
