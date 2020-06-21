# Mexico's Covid19 Patitients data organizer
 This system takes the Mexico official daily patients data, and produces data bases for confirmed, suspicious, negatives, deaths, actives, hospitalized and ongoing patients.

 So thing is, every day the official data can be found here:


<a href="https://coronavirus.gob.mx/datos/#DownZCSV" rel="photo of data source">![photo of data source](https://i.imgur.com/6QXgprd.png)</a>

From there you can download this csv's:
![](https://i.imgur.com/P2bI0uq.png)

But if you need data from passed days, you can only get the patients data, without the other ones, from here:  

<a href="https://www.gob.mx/salud/documentos/datos-abiertos-bases-historicas-direccion-general-de-epidemiologia" rel="photo of data source">![photo of data source](https://i.imgur.com/kFvZyjF.png)</a>

Also the official confirmed, suspicious, negatives and deaths csv's, are not that accurate, they suffer from some compresion, like they record less cases on the weekend and human stuff like that. With this functions you can have the csv's with more accurate data.  
This is a comparation of both:  

![photo of data source](https://i.imgur.com/npwHBRa.png)  

Also this sytem provides you with three more csv's for Hospitalized, Ongoing and Active patients.  

## Instructions:
To run it you'll need the csv of all patients that is named like that:  

```%y%m%dCOVID19MEXICO.csv```  

That file goes into the 'in' folder. You can put several files at once, so you can generate different days at once.

To run it from the console, assuming you already have the input files in the 'in' folder, just type:

```python
python covid19_data_organizer.py

```
And that should be all, no parameters need it.

To run it from Jupyter Notebook, open your jupyter notebook on the same folder as this repository and open this notebook. 

And that's all, any issue please go to: issues.



