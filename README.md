# s8-comm

Purpose: illustrate issues that can occur with properties

KnowledgeBase does not have it's own logic: it acts as a "pass-through" component

Problem: we have unnecessary pass through - KnowledgeBase should not need props or events

we can use Provide and Inject:

Provide data in one place
Inject data (use it) in another place