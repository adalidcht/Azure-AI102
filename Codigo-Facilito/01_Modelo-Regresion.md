# Modelo de regresión con el diseñador
## 1. Compute
Setting | Selected
--- | ---
Virtual machine tier | Dedicated
Virtual machine type | CPU
Virtual machine size | DS11_v2
Min. Nodes | 0
Max. Nodes | 2
Idle seconds before scale down | 120

## 2. Designer
- Create
  - Components
    - Sample Data
      - Automobile Price Data (Raw)
    - Data Transformations
      - Select Columns in Dataset
        - by name
        - add all
        -  \- normalized losses
      - Clear missing data
        - Column names: bore,stroke,horsepower
        - Cleaning mode: Remove entire row
      - 
