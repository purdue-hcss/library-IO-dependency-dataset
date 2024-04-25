# Libraries.io data dump
The original data dump of libraries.io consists of several csv files, each contains information such as dependencies, projects, repositories, tags, and versions. There are also multiple versions of the data dump from the year of 2017 to 2020. Due to size limit (the 2020 data dump is ~25GB after compression), `libraries_io_dependencies_data.json` only containing the first 100,000 dependencies from the 2017 data dump for you to play with. To download the complete data dumps or more information on the data dumps, please visit https://zenodo.org/records/808273.

To help the hackathon participants navigate the json file, we explain each field as below.
- `ID`: Unique identifier for the record. This is used in the `projects-xxx.csv` file from the data dump.
- `Platform`: The package manager for the project.
- `Project Name`: Name of the project.
- `Project ID`: Unique identifier for the project within its platform.
- `Version Number`: Specific version number of the project.
- `Version ID`: Unique identifier for the version. This is used in the `version-xxx.csv` file from the data dump.
- `Dependency Name`: Name of the dependency, typically referring to required libraries or packages.
- `Dependency Platform`: The technology platform of the dependency.
- `Dependency Kind`: Type of dependency, such as runtime or development.
- `Optional Dependency`: Indicates whether the dependency is optional, often used for non-essential feature extensions.
- `Dependency Requirements`: Specifies requirements for the dependency, like version constraints.
- `Dependency Project ID`: Unique identifier for the dependency project. This is used in the `projects-xxx.csv` file from the data dump.

