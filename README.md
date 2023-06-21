# poc
A proof of concept for aggregate DB.

## Tech stack
1. Java console application
2. Junit for unit tests


## Phase I
1. Create a Java application that does an in-memory storage for time series data, and prepopulate with randomly generated values
2. Add ability to compute average within specified window, with ability to specify open, semi open and closed ranges
3. Add ability to insert additional data at arbitrary points in the time series
4. Use object oriented design, prefer functional programming principles

## Phase II
1. Implement preaggregation for average
2. Compute preaggregates during insertion
