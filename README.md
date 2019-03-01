# postgrest_dockerfile_now.zeit
Simple and minimal dockerfile example to configure now.zeit to act as endpoint for a REST webservice with Postgresql database outside NOW. 

First configure your database and make a schema to get the requests. Create a role and grant this schema with right permissions. Reserve.
Put in your dockerfile apropriate credencials, like IP, user/password, database, API schema and role name.

It works like a charm!. 
