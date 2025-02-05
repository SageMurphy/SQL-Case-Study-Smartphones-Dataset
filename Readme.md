# Smartphone Specs Case Study

## Project Overview
This project analyzes a dataset of smartphone specifications. It involves data cleaning, SQL queries, and insights into smartphone brands, models, features, and sales.

## Features
- Data cleaning and preprocessing using Pandas
- SQL queries to extract insights from the dataset
- Sales analysis and trend identification
- Battery life, camera, and performance analysis

## Dataset Columns
The dataset contains the following columns:
- **Unnamed: 0**: Index column
- **Brand**: Smartphone brand
- **Model**: Smartphone model name
- **Released**: Release date of the smartphone
- **Announced**: Announcement date
- **Hardware Designer**: Company responsible for hardware design
- **Manufacturer**: Manufacturer of the smartphone
- **General Extras**: Additional features
- **Width, Height, Depth, Dimensions**: Physical dimensions of the smartphone
- **Mass**: Weight of the smartphone
- **Platform**: Platform information
- **Operating System**: OS version
- **CPU Clock**: Clock speed of the processor
- **CPU**: Processor model
- **RAM Type**: Type of RAM used
- **RAM Capacity (converted)**: RAM size in standardized format
- **Non-volatile Memory Interface**: Storage type used
- **Display Diagonal**: Screen size in inches
- **Resolution**: Screen resolution
- **Pixel Density**: Pixels per inch
- **Display Area Utilization**: Screen-to-body ratio
- **Display Type**: Type of display panel
- **Display Refresh Rate**: Refresh rate of the display
- **Scratch Resistant Screen**: Indicates if the screen is scratch-resistant
- **Graphical Controller**: Graphics processing unit
- **GPU Clock**: Clock speed of the GPU
- **Expansion Interfaces**: External expansion options
- **USB Services**: USB-related features
- **USB Connector**: Type of USB port
- **Max. Charging Power**: Maximum supported charging power
- **Bluetooth**: Bluetooth version
- **Camera Placement**: Camera placement details
- **Camera Image Sensor**: Type of image sensor
- **Image Sensor Pixel Size**: Pixel size of the camera sensor
- **Aperture (W)**: Camera aperture size
- **Zoom**: Zoom capabilities
- **Video Recording**: Video recording capabilities
- **Camera Extra Functions**: Additional camera features
- **Secondary Video Recording**: Secondary camera video recording details
- **Nominal Battery Capacity**: Battery capacity in mAh
- **Estimated Battery Life**: Estimated battery duration
- **Market Countries**: Countries where the model is available
- **Market Regions**: Regions where the model is sold
- **Price**: Price of the smartphone
- **Memory Capacity**: Internal storage capacity
- **Cam1_mp**: Primary camera megapixels
- **Cam2_mp**: Secondary camera megapixels

## Installation
```bash
pip install -r requirements.txt
```

## Usage
1. Load the dataset using Pandas.
2. Run the provided SQL queries in a database environment.
3. Analyze the results and generate insights.

## Files
- `mobile.csv` - Raw dataset
- `Cleaned_Mobile.csv` - Processed dataset
- `units_sold.csv` - Simulated sales data
- `queries.sql` - SQL queries used for analysis
- `requirements.txt` - List of dependencies
- `LICENSE` - Project licensing details
- `.gitignore` - Files to exclude from Git version control

## Requirements
```
pandas
sqlalchemy
pymysql
cryptography
```

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Author
Abhishek Shrimali
