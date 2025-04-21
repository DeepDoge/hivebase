hivebase, scalable from 1 to infinity  
user and dev friendly database/backend and client sdk, done right

this will be a pocketbase/firebase alternative  
more code oriented so you can actually commit your database schema with your code  
but has a dev ui which lets you update the schema and push changes to your hivebase nodes

so you will have a local schema file  
dev ui will edit that file in the dev environment  
then you can push those changes to the nodes/servers

designed to remove the need for any server code as much as possible  
designed to scale to multiple hivebase nodes

comes with a powerful typescript sdk  
removes the need for designing your own system on top of hivebase sdk as much as possible  
probably that would be a separate package on top of the core sdk  
it will be more complete, production ready  
would create a replica of the database locally via indexeddb probably  
maybe with a plugin again  
so good caching

rules are more close to sql building  
you can do math and conditions  
no get and list rules  
just general filtering rules  
acts kinda like a sql builder with subqueries

mutation rules are different  
tbh rules are written with code  
yeah  
better  
they let you edit user request input or output or both  
middleware style

no external dependencies  
made with deno

supports everything pocketbase supports  
custom auth options via plugins  
custom email / sms / whatsapp / discord / etc services via plugins

more interactive migrations with scripts when needed  
right in the web dev ui

will be refined more as we build more projects for customers with this

i’ll probably start writing this at the end of the summer  
after i write more important things to me
