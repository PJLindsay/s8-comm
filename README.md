# s8-comm

Purpose: illustrate issues that can occur with properties

KnowledgeBase does not have it's own logic: it acts as a "pass-through" component

Problem: we have unnecessary pass through - KnowledgeBase should not need props or events

we can use Provide and Inject:

Provide data in one place
Inject data (use it) in another place

we can also use provide and inject with methods/function (parent-child but not neighbour/sibling)

typically we would use props and events, but we can use Provide and Inject if you have pass-through components (a more complex hierarchy such as grandparents, etc.)