# Agent Tags

Tagging allows organizations to group agents together by using a meaningful name, the
default tag for a Lightrun agent is “Production”.Tags enable users to map their own organizational structures onto system 
objects in a loosely coupled fashion, without requiring clients to 
store these mappings.

Service deployments and batch processing pipelines are often multi-dimensional entities (e.g., multiple partitions or deployments, multiple release tracks, multiple tiers, multiple micro-services per tier). Management often requires cross-cutting operations, which breaks encapsulation of strictly hierarchical representations, especially rigid hierarchies determined by the infrastructure rather than by users.

Tags are key/value pairs that are attached to objects, such as pods. 
Tags are intended to be used to specify identifying attributes of 
objects that are meaningful and relevant to users, but do not directly 
imply semantics to the core system. Tags can be used to organize and to 
select subsets of objects. Tags can be attached to objects at creation 
time and subsequently added and modified at any time. Each object can have
a set of key/value Tags defined. Each Key must be unique for a given object.

A Lightrun agent can be launched with one or more tags. 

Actions that are added to an agent are deleted once the agent disconnects 
from the Lightrun server. Actions that are added to tags are persistent.
