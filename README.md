# planning-queue
A place to manage issues that do not have a dedicated repository or code... yet.

## Handy filters to use in a project view
- `is:open` - Displays only open issues

- `assignee: @me` - Displays issues assigned to the logged in user

- `is:open assignee:@me` - Combining the two above filters will display only open issues assigned to the logged in user

- `program-increment:"FY25-Q3"` - Will filter by the specified quarter

- `team:Dev,"Data+Dev"` - Allows you to choose your team or teams (the comma acts as an OR statement)

- `no:q3-sprint` - Shows what issues haven't been assigned a sprint

- `is:open program-increment:"FY25-Q3" no:q3-sprint` - Will display issues unassigned to a sprint within a given quarter

- `is:open program-increment:"FY25-Q3" q3-sprint:"Q3 Sprint 2"` - Shows open issues in the current sprint (in this example, the sprint is _Q3 Sprint 2_)

A comprehensive list of filter options can be found [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/filtering-projects).
