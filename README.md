# resource
- clients,
- meeetings

# attributes for clients
  - clientname,
  - address,
  - phone,
  - email

# attributes for meetings
- fname
- atime

# table

  Methods      | paths | Name
  ------------ | ------|------
  GET  | /clients | list all clients
  POST | /clients | creats a new client
  PUT | /clients/:id | update a client
  DELETE | /clients/:id | removes a client
  GET  | /meetings | list all meetings
  POST | /meeetings | creates a new meeting
  DELETE | /meetings/:id | removes a meeting
