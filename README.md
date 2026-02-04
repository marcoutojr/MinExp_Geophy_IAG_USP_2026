# Mineral Exploration Geophysics - IAG-USP Geophysics Summer School 2026

Repository to organize the coding material for the course Mineral Exploration Geophysics IAG Geophysics Summer School 2026

## Material used in this reposity

 - The open-source material used for the Century deposit example comes from the [Transform 2020 tutorial][https://github.com/simpeg/transform-2020-simpeg/tree/main]. Only an update to export the inversion results to the [Mira Geoscience Analyst was made][].
 - For the inversion examples in [SimPEG][https://simpeg.xyz/] course, we used open-source material from the [official documentation][https://docs.simpeg.xyz/latest/] and [user tutorials][https://simpeg.xyz/user-tutorials/], namely:
	- [`inv_magnetics_induced_3d.ipynb`][https://simpeg.xyz/user-tutorials/inv-magnetics-induced-3d/] and;
	- [`plot_inv_mag_MVI_Sparse_TreeMesh.ipynb`][https://docs.simpeg.xyz/latest/content/user-guide/examples/03-magnetics/plot_inv_mag_MVI_Sparse_TreeMesh.html]

## To install the requirements to run the code stored here, run on your terminal (you can also navigate through the terminal to the directory you want download it):

```
git clone https://github.com/marcoutojr/MinExp_Geophy_IAG_USP_2026.git
```

Then, on your terminal:
```
cd MinExp_Geophy_IAG_USP_2026
```

Inside the folder, run:
```
conda env create -f veraoiag2026.yml
```

Done, you should be good to go! Have fun!