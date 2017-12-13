# ICRP-Extended
On going work regarding ICRP Population improvement based on [this](https://github.com/Open-Systems-Pharmacology/Forum/issues/87)  discussion in the forum

## How to use the database

* Close PK-Sim application.
* Go to folder  `C:\ProgramData\Open Systems Pharmacology\PK-Sim\7.2`
* Create a copy of the `PKSimDB.mdb` file (so that you can revert at any time to the installation version of the model database)
* Copy the file `PKSimDB.mdb` from this repository into folder `C:\ProgramData\Open Systems Pharmacology\PK-Sim\7.2`
* Restart PK-Sim. You should have a ICRP Extended Population available
![image](https://user-images.githubusercontent.com/1041237/33950767-392ec1e4-dffb-11e7-96a2-68683cbad183.png)


The list of all age dependent parameters for the ICRP Population can also be found in ICRP Parameters.xlsx. This table is nothing more than an extract of the database table called `TAB_CONTAINER_PARAMETER_CURVES`. To see all parameters for the ICRP Extended popuation, simply do as follow

* Open PKSimDB.mdb (Access required)
* Open table `TAB_CONTAINER_PARAMETER_CURVES` (double click on table)
* Go to the population column and filter by `ICRP_Extended` (Click first on `select all` to deselect all entries then select ICRP_Extended)

![image](https://user-images.githubusercontent.com/1041237/33950940-a5aa7e94-dffb-11e7-9e45-c3872fbdd761.png)
* To see all `Volume` parameters for example, filter by parameter name `Volume`. This should return all available data points for each organ volume 



## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md). If you are contributing code, please be familiar with the [coding standards](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md).
