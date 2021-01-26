# M3-MinimalistMixtureModel
# CODES AND TECHNICAL DESCRIPTION OF THE MINIMALIST MIXTURE MODEL (M3)

# Contacts: Herman Berghuijs (herman.berghuijs@wur.nl); Giulia Vico (giulia.vico@slu.se)

For the model rationale, calibration and validation see
Berghuijs HNC, Wang Z, Stomph TJ, Weih M, Van der Werf W, Vico G (2020), Identification of crop traits enhancing wheat-faba bean intercrop productivity: a crop growth model and sensitivity analyses, Plant and Soil, 455, 203–226, https://doi.org/10.1007/s11104-020-04668-0

# CONTENT

M3_source_code.zip contains the source code, the executable, and a sample of input files.
M3_TechnicalDescription_BerghuijsVico_Jan2021.pdf contains a technical description of all the model components.

# MODEL RUNNING

M3 can be run as follows:
- If M3 is used for the first time, unpack M3_source_code.zip at a chosen location.
- Navigate to ...\M3_source_code\M3\RunSimulationsFromInputFile\bin\Debug
- Run the file "RunSimulationsFromInputFile.exe" 

This will run all the simulations that are specified in the file "...\M3_source_code\M3\RunSimulationsFromInputFile\bin\Debug\simulationInput.csv". The output files from the simulations will be saved in the folder  ""...\M3_source_code\M3\RunSimulationsFromInputFile\bin\Debug\Output files".
M3 source.zip contains, besides the model, also a number of input files for sample simulations. More information on the structure of these input files can be found in Section 8 in the Technical description.


This model was developed as part of the project DIVERSify, funded from the European Union’s Horizon 2020 Research and Innovation Programme under grant agreement 727284.
More information on the project and its results are available at https://www.plant-teams.eu/
