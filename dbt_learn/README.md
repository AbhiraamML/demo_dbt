Welcome to your new dbt project!

Install SSMS and SQL Server Client from Microsoft Website

pip install dbt-core
pip install dbt-sqlserver

dbt --version
dbt init dbtlearn

The project Connects to "sqlserver_profile" defined in profiles.yml and dbt_project.yml file. 

We ran "dbt init dblearn" that created the base template file structure for development

We ran "dbt debug --profile sqlserver_profile" command that validated only the profile connections

We ran "dbt debug" command that validated all files including the dbt_project.yml and stated that profile name does not match.

We ran "dbt run" that executed the models

We ran "dbt test" that validated "schema.yml" and shared the results


### DBT Commands

Commands:
  build          Run all seeds, models, snapshots, and tests in DAG order
  clean          Delete all folders in the clean-targets list (usually...
  clone          Create clones of selected nodes based on their location...
  compile        Generates executable SQL from source, model, test, and...
    debug          Show information on the current dbt environment and...
  deps           Install dbt packages specified.
  docs           Generate or serve the documentation website for your...
    init           Initialize a new dbt project.
  list           List the resources in your project
  parse          Parses the project and provides information on performance
  retry          Retry the nodes that failed in the previous run.
    run            Compile SQL and execute against the current target...
  run-operation  Run the named macro with any supplied arguments.
  seed           Load data from csv files into your data warehouse.
  show           Generates executable SQL for a named resource or inline...
  snapshot       Execute snapshots defined in your project
  source         Manage your project's sources
    test           Runs tests on data in deployed models based on schema.yml file 

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
