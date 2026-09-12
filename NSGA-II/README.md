# NSGA-II for Job Shop Scheduling

The [NSGA-II notebook](NSGA-II_implementation.ipynb) is an early multi-objective scheduling experiment with non-dominated sorting, crowding distance, crossover, mutation, and survivor selection.

Read the [JSP overview](https://github.com/okumochu/Flexible-Job-Shop-Scheduling/blob/main/job-shop/README.md) before running it. In particular, the original input configuration loads the machine-sequence CSV for all three data frames and must be reviewed before a complete run.

The fitness function returns makespan and the sum of absolute deviations between job completion times and due dates. The second objective is named `twet` in the code, but priority weights are not applied.

## Original process diagram

![NSGA-II process](NSGA-II%20proccess.png)

The saved plots show objective values over iterations. They do not visualize the Pareto frontier; a frontier plot was identified as unfinished work in the original project.

Saved notebook outputs and algorithm settings are retained for historical reference.
