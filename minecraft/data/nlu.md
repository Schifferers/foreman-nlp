## intent:start
- Start the [vanilla](server_id) server
- Start the [snapshot](server_id) server
- Start the [hardcore](server_id) server
- Start the [lotr](server_id) server
- Start the [kids](server_id) server
- Run the [vanilla](server_id) server
- Get the [vanilla](server_id) server going
- Boot the [vanilla](server_id) server
- Start [vanilla](server_id)

## intent:stop
- Stop the [vanilla](server_id) server
- Stop the [snapshot](server_id) server
- Stop the [hardcore](server_id) server
- Stop the [lotr](server_id:lotr) server
- Stop the [kids](server_id:kids) server
- Bring the server [vanilla](server_id) down
- Shutdown the [hardcore](server_id) server
- Stop [vanilla](server_id)

## synonym:lotr
- Lord of the Rings
- Middle-Earth
- Middle Earth
- Tolkien

## intent:reset
- Reset the [hardcore](server_id) server
- Reset [vanilla](server_id)
- Clean up the [hardcore](server_id) server
- Erase the [hardcore](server_id) server
- Erase [vanilla](server_id)
- Purge the [hardcore](server_id) server
- Purge [vanilla](server_id)

## intent:upgrade
- Upgrade the [vanilla](server_id) server to version the [latest](version) version
- Upgrade the [vanilla](server_id) server to version [1.15](version)
- Upgrade the [snapshot](server_id) server to the latest version
- Upgrade [vanilla](server_id) to [1.16](version)

## intent:status
- What is the status of the [snapshot](server_id) server?
- How is the [lotr](server_id) server doing?
- What's going on with the [vanilla](server_id) server?
- Status [vanilla](server_id)
- What about the [hardcore](server_id) server?
- Tell me about the [snapshot](server_id) server?
- Server status
- server condition
- status
- minecraft status
- is the server up?
- is the server down?
- are the servers down?
- what is going on with the server?

## intent:list
- What servers are there?
- Which servers are configured?
- Tell me the servers
- List the servers
- Show the servers
- Servers
- list
- show
- server list
- inventory

## regex:server_id
- \\w+

## regex:version
- \\d+\\.\\d+(\\.\\d+)?
- latest

