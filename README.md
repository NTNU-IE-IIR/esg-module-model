# ESG Module model

Machine learning model project for the ESG module in
[FisheryInsight](https://ncmc.no/digitalisere-hel-fiskerin-ringen/). The project is done as part of
the bachelor thesis by group 14.

### How to run

To run the machine learning model application, you need to have Anaconda installed. If you do not
have Anaconda installed, you can download the installation
[here](https://www.anaconda.com/download).

Once you have Anaconda installed, you need to set up the Anaconda environment for the application.
Run the following command to install the Anaconda enviroment:

```
conda env create -f environment.yml -p <your-environment-directory>/modelenv
```

**Note:** On Windows, the default Anaconda environment directory is located at
`C:/Users/<your-user>/anaconda3/envs`. If you want to use the default environment directory, use
this path in `<your-environment-directory>`.

Once the environment is set up, you need to select it as the kernel source for the `model.ipynb`
file, and either run the file in your Jupyter Notebook interface or by running the following
command:

```
jupyter execute model.ipynb
```
