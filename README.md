# AEM_graphQl_Voyager
The package will install GraphQL Voyager in your AEM Instance to visualize your content fragment relationships.

## Why
We use a lot of content fragments in our projects. Often these are complexly connected with each other.
To avoid losing track of which content fragment is connected to which one, you can use the GraphQL Voager to get a good overview.

## What is GraphQL Voyager
_Taken from https://github.com/APIs-guru/graphql-voyager:_
With graphql-voyager you can visually explore your GraphQL API as an interactive graph. This is a great tool when designing or discussing your data model.

## How to use
It installs https://github.com/APIs-guru/graphql-voyager under /apps and adds a new icon "GraphQL Voyager" under /assets/.

Under AEM -> Assets you will get a new Icon "GraphQL Voyager". Click on that, select your endpoint in the dropdown and you will see your content fragment relationships.

## Demo
https://jmp.sh/XbUsMUV

## How to install
**Localhost**: just upload via package manager http://localhost:4502/crx/packmgr/index.jsp

**Cloud**: This needs to be deployed since /apps/ is an immutable folder.

## Requirements
* Tested with AEM Cloud SDK 2021.10 and AEM 6.5.10
* Optional for testing: Latest https://github.com/adobe/aem-guides-wknd/releases/tag/aem-guides-wknd-1.0.0 
