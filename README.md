## Project outline

This will be a simple app in which to develop lib files that will turn into a pivotal api gem. Optionally, we might add some behavior to provide persistance of pivotal objects and build this into a mountable Rails engine.

### To do

1. Add creds for a test pivotal account
2. Create a simple library for instantiating an API agent
3. Agents carry user creds and make requests in a threadsafe way
4. Add libraries to mix-in API-specific HTTP requests to pivotaltracker.com
