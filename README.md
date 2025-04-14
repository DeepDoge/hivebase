This will be a pocketbase/firebase alternative. More code orianted so you can actually commit your database schema with your code, but has dev ui which lets you update the schema and push changes to your minibase nodes.
Designed to remove need for any server code as much as posibble.
Designed to be able to scale to multiple minibase nodes.

and comes with a powerful TypeScript SDK, which removes the need for designing your own system on top of minibase sdk as much as posibble.
probably that would be a seperate package on top of the core sdk.

with rules more close to sql building where you can do math and conditions.

no external dependencies, made with deno.

support everything pocketbase supports.
custom auth options via plugins.
custom email/sms/whatsapp/discord/etc services via plugins.

more interactive migrations with scripts when needed right in the web dev ui.

will be refined more as we build more projects for the customers with this.


I will probably start writing this at the end of the summer. After I write more import things to me.
