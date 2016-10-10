#Hypergoal sample payloads

## Overview
The samples here represent an event booking use case. The client in this case is trying to book to attend RESTFest. 

## Files

* goal.json - The goal the client is trying to achieve. This is sent to a goal agent who responsibility is to guide the client. 
* event.json - Descriptor for the event. This is the information that would be hosted at `https://restfest.org/event`
* goalagent1.json, goalagent2.json - A document will capture the entire "journey" toward the goal and passed back and forth between the client and goal agent. This document contains all the state for the interactions. These 2 documents are examples at different points during the journey.
