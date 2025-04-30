# Marriage Cube

## Description
This project implements an OLAP (Online Analytical Processing) cube for analyzing marriage-related data. The cube enables multidimensional queries and provides insights into various aspects of marriages, such as marriage type, region, occupation, and more.

## Project Structure
- **Cubo_Matrimonios.database**: Contains the database definition for the cube.
- **BI.ds**: Data source file used to connect to the database.
- **BI.dsv**: Data source view defining relationships between tables.
- **Dimensions**:
  - **Matrimonios Dim Anno Trabajo.dim**: Groups data by work year.
  - **Matrimonios Dim Ocupacion.dim**: Classifies data by occupation.
  - **Matrimonios Dim Region Matrimonio.dim**: Organizes data by marriage region.
  - **Matrimonios Dim Tipo Matrimonio.dim**: Categorizes data by marriage type.
  - **Matrimonios Dim Tipo Pareja.dim**: Classifies data by couple type.
- **CuboMatrimonios.cube**: Defines the OLAP cube structure.
- **CuboMatrimonios.partitions**: Contains cube partitions for performance optimization.

## Requirements
- **Tools**:
  - Visual Studio 2022
  - SQL Server Analysis Services (SSAS)
- **Dependencies**:
  - A database containing the input data for the cube.

## Installation
1. Clone this repository to your local machine.
2. Open the project in Visual Studio 2022.
3. Configure the database connection in the `BI.ds` file.
4. Deploy the cube to an SSAS server.

## Usage
1. Connect an analysis client (e.g., Excel or Power BI) to the SSAS server.
2. Perform multidimensional queries using the dimensions and measures defined in the cube.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request if you'd like to contribute.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact
For questions or support, please contact [your email or name here].
