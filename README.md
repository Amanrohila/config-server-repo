# config-server-repo
# open browser and check below Urls, it will return the JSON output and in propertySources section
http://localhost:8888/config-server-client/development
http://localhost:8888/config-server-client/production

# something like below
{
name: "config-server-client",
profiles: [
"development"
],
label: null,
version: "5dda1ac519839b2b8b86ed9bde3f8e0c9764b65d",
state: null,
propertySources: [
{
name: "D:\gitrepositories\config-server-repo/config-server-client-development.properties",
source: {
msg: "Hello world - this is from config server - Development Env ssw"
}
},
{
name: "D:\gitrepositories\config-server-repo/config-server-client.properties",
source: {
msg: "Hello world - this is from config server"
}
}
]
}