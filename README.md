# postgrest_dockerfile_now.zeit
Simple and minimal dockerfile example to configure now.zeit to act as endpoint for a REST webservice with Postgresql database outside NOW. 

First configure your database and make a schema to get/post the API requests. Create a role and grant this schema right permissions. 

Put in your dockerfile apropriate credencials, like IP, user/password, database, API schema and role name. Must have now.json file v1.

It works like a charm!. 
