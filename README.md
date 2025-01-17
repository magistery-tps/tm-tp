
<p align="left">
<b>University of Buenos Aires (UBA)</br>Master in Data Mining and Knowledge Discovery<br/> Series temporales</b>
</p>

# Predicción del consumo de energía eléctrica en GBA


## Notebooks

* **EDA**
  * **Demanda Energetica**
      * [Python](https://github.com/magistery-tps/tm-tp/blob/master/notebooks/EDA_ff.ipynb)
      * [R](https://github.com/magistery-tps/tm-tp/blob/master/notebooks/EDA_funcionesR.ipynb)
  * **Tarifas**
    * [Scraping](https://github.com/magistery-tps/time-series-tp/blob/master/notebooks/tarifas-scraping.ipynb)
    * [Análisis](https://github.com/magistery-tps/tm-tp/blob/master/notebooks/tarifas-eda.ipynb)
 
* **Modelos**
  * [LSTM](https://github.com/magistery-tps/tm-tp/blob/master/notebooks/prediction-lstm.ipynb)
  * [Prophet](https://github.com/magistery-tps/tm-tp/blob/master/notebooks/prediction_prophet.ipynb)
  * [Prophet: CDD y HDD como variables predictoras](https://github.com/magistery-tps/time-series-tp/blob/master/notebooks/prediction_prophet_CDD_HDD.ipynb)
  * [Prophet Simple: CDD y HDD como variables predictoras](https://github.com/magistery-tps/time-series-tp/blob/master/notebooks/prediction_simple_prophet_CDD_HDD.ipynb)
  * [Modelo Hibrido (Ensample)](https://github.com/magistery-tps/time-series-tp/blob/master/notebooks/prediction_modelo_hibrido.ipynb)
  * [Kats](https://github.com/magistery-tps/time-series-tp/blob/master/notebooks/analisis_prediccion_kats.ipynb)
  * [NBeats](https://github.com/magistery-tps/time-series-tp/blob/master/notebooks/predictions-nbeats.ipynb)


## Requisites

* [anaconda](https://www.anaconda.com/products/individual) / [miniconda](https://docs.conda.io/en/latest/miniconda.html) / [mamba (Recomendado)](https://github.com/mamba-org/mamba)
* [Setup de entorno (Window)](https://www.youtube.com/watch?v=O8YXuHNdIIk)

## Getting started

**Step 1**: Clone repo.

```bash
$ git clone https://github.com/magistery-tps/time-series.git
$ cd time-series
```

**Step 2**: Create environment.

```bash
$ conda env create -f environment.yml
```

## See notebooks in jupyter lab

**Step 1**: Enable project environment.

```bash
$ conda activate time-series
```

**Step 2**: Under project directory boot jupyter lab.

```bash
$ jupyter lab

Jupyter Notebook 6.1.4 is running at:
http://localhost:8888/?token=45efe99607fa6......
```

**Step 3**: Go to http://localhost:8888.... as indicated in the shell output.

