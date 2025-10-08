# PCA Analysis: CO2 Emissions and Economic Indicators

## 📊 Dataset Description

### Source & Context
This analysis uses country-level data combining economic indicators with CO2 emission sources to understand patterns between economic development and environmental impact.

### Variables Analyzed (15 Numerical Features)

#### Economic Indicators:
- **Population** - Country population size
- **GDP PER CAPITA (USD)** - Economic output per person
- **GDP PER CAPITA PPP (USD)** - Purchasing power parity adjusted GDP
- **Area (Km²)** - Country land area

#### CO2 Emission Sources (in Metric Tons):
- **Transportation** - Emissions from transport sector
- **Total CO2 Emission including LUCF** - Total emissions with land-use changes
- **Total CO2 Emission excluding LUCF** - Total emissions without land-use changes
- **Other Fuel Combustion** - Emissions from other fuel sources
- **Manufacturing/Construction** - Industrial process emissions
- **Land-Use Change and Forestry** - Emissions from land use changes
- **Industrial Processes** - Manufacturing emissions
- **Energy** - Energy sector emissions
- **Electricity/Heat** - Power generation emissions
- **Bunker Fuels** - Shipping and aviation emissions
- **Building** - Residential and commercial building emissions

### Data Characteristics:
- **Samples**: 1,134 country-year observations
- **Features**: 15 numerical variables
- **Missing Values**: Handled via median imputation
- **Excluded**: 'Year' and 'Fugitive Emissions' due to relevance and excessive missing data

## 🔄 Step-by-Step PCA Process

### 1. Data Preprocessing
### 2. Data Standardization
### 3. PCA Implementation
### 4. Data visualisation of the before and after the PCA
