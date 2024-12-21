# DBT Fundamentals Course Documentation

This repository contains the work completed during the DBT Fundamentals course administered by DBT Labs via DBT Learn. The course provides an introduction to DBT, teaching fundamental concepts and best practices for data transformation in the analytics workflow.

### Course Highlights
- Introduction to DBT and its capabilities.
- Hands-on experience with data models, testing, and documentation.
- Learning how to run and manage DBT projects and workflows.
- Exploration of DBT's integration with version control and deployment practices.

### Project Files and Structure
The repository includes the following:
- **dbt_project.yml**: Configuration file for DBT projects.
- **models/**: Contains SQL files representing DBT models created during the course.
- **tests/**: Unit tests for validating data models and transformations.
- **docs/**: Documentation on the models, tests, and project setup.

### How to Use
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/dbt-fundamentals
    cd dbt-fundamentals
    ```

2. **Set Up DBT Environment**:
    Follow the instructions to set up DBT on your local machine using the official [DBT installation guide](https://docs.getdbt.com/docs/installation).

3. **Run DBT Models**:
    After configuring your data warehouse connection (e.g., BigQuery, Snowflake, Redshift, etc.), run the DBT models:
    ```bash
    dbt run
    ```

4. **Testing Models**:
    Run DBT tests to validate the correctness of the models:
    ```bash
    dbt test
    ```

5. **Generate Documentation**:
    Generate the DBT documentation for models and dependencies:
    ```bash
    dbt docs generate
    dbt docs serve
    ```

