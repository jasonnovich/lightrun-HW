# Agent Tags
 
Configuring your agent to use tags help you better visualize 
and troubleshoot specific parts of your live running code. 
Using the agent's tag, you can map your organizational structure onto system
objects without requiring the client to store these mappings.

## Use Cases

When you use tags, it is easy to then group agents together using a
meaningful name. It is important to name the tags in such a way that they are easily identifiable and 
are meaningful and relevant to users. It is common to name tags based on common functionality. For example:
- Location of the agent (for example "east-coast-usa")
- Purpose of the agent (for example, "counter-tracking")
- Running environment of the agent (for example, "Production", "Staging", etc.)

You can configure multiple tags per agent to maximize efficiency in grouping agents' functionality.
Once you have tagged your agents, they can then be filtered either through your IDE or from the command line. 
[Lightrun Actions](https://docs.lightrun.com/actions/) can be bound to your tag so that you can trigger a request 
to the agents that have that tag. This way agents can dynamically insert logs, metrics, and other snapshots 
into production code. Actions that are bound to a tag are implicitly added to all agents that possess that tag.

## Recommendations
- Create tags that share common attributes that you will want to track.
- Bind a [Lightrun Action](https://docs.lightrun.com/actions/) to the tag so that all agents with that tag are traceable.
- 