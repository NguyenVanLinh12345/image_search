# Code image search
![Tham khao](https://github.com/astrodestroyergithub/Image-Search-Engine/)

# step 1
pip install -r requirements.txt

# step 2
cd course

# Step 3 Train:
python3 index.py -d ../images/ -i ../index/index.csv

# Step 4 Search:
python3 search.py -i ../index/index.csv -q ../query/qimg1.png -r ../images/

