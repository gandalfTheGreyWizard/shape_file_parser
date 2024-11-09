##### Setup
1. create a virtual environment 
```bash
python3 -m venv venv
```
2. activate the virtual environment
```bash
source venv/bin/activate
```
3. install the requirements
```bash
pip install -r requirements.txt
```
4. run the app
```bash
python shape_files_parser.py -i [input_data_directory] -o [output_data_directory]
```
> Note: The input data directory should contain all the shp files that need to be parsed and the output directory will be referenced to store the parsed geojson data
