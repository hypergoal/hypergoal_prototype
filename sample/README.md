#Hypergoal sample payloads

## Overview
The samples here represent an event booking use case. The client in this case is trying to book to attend RESTFest. 

## Usage of JSON-LD
JSON-LD is used within to attach semantic meaning to each of the elements. The JSON-LD docs themselves do not exist yet and the references are purely for illustration.

## Files

* goal.json - The goal the client is trying to achieve. This is sent to a goal agent who responsibility is to guide the client. 
* event.json - Descriptor for the event. This is the information that would be hosted at `https://restfest.org/event`
* goalagent1.json, goalagent2.json - Examples of payloads at different stages through the workflow. A document will capture all the state for the "journey" toward the goal. It will be passed back and forth between the client and goal agent and continually appended / updated.
