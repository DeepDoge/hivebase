This will be a pocketbase/firebase alternative. More code orianted so you can actually commit your database schema with your code, but has dev ui which lets you update the schema and push changes to your minibase nodes.
So you will have a local schema file, dev ui will edit that file in the dev envoriment, then you can push those changes to the nodes/servers.
Designed to remove need for any server code as much as posibble.
Designed to be able to scale to multiple minibase nodes.

and comes with a powerful TypeScript SDK, which removes the need for designing your own system on top of minibase sdk as much as posibble.
probably that would be a seperate package on top of the core sdk. it will be more complate, production ready.
it would create a replica of the database locally via indexeddb probably, maybe with a plugin again. so good caching.

with rules more close to sql building where you can do math and conditions.
there is no get and list rules, just filtering rules in general, it will act kinda like a sql builder with sub queries.
mutation rules are different.
tbh rules are writing with code. yeah. better.
they let you edit user request input or output or both. middleware style.

no external dependencies, made with deno.

support everything pocketbase supports.
custom auth options via plugins.
custom email/sms/whatsapp/discord/etc services via plugins.

more interactive migrations with scripts when needed right in the web dev ui.

will be refined more as we build more projects for the customers with this.


I will probably start writing this at the end of the summer. After I write more import things to me.
