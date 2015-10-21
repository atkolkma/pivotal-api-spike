## Project outline

This will be a simple app in which to develop lib files that will turn into a pivotal api gem. Optionally, we might add some behavior to provide persistance of pivotal objects and build this into a mountable Rails engine.

### Previous Examples.

We should look at stealing good ideas/archetectire from existing pivotal api gems. 
The two major ones are:
- https://github.com/jsmestad/pivotal-tracker
- https://github.com/dashofcode/tracker_api
There's also this work in progress:
- https://github.com/atljeremy/pivotal-tracker-api

### To do

1. Add creds for a test pivotal account
2. Create a simple library for instantiating an API agent
3. Agents carry user creds and make requests in a threadsafe way
4. Add libraries to mix-in API-specific HTTP requests to pivotaltracker.com
