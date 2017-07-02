<% const camelcasedName = this.camelcase(name) -%>
<% const normalUserName = username.toLowerCase() -%>
# <%= name %>

> <%= description %>

## License

**<%= name %>** © [<%= username %>](https://github.com/<%= normalUserName %>), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by <%= username %> with help from contributors ([list](https://github.com/<%= normalUserName %>/<%= name %>/contributors)).

> [<%= website.replace(/^https?:\/\//, '') %>](<%= website %>) · GitHub [@<%= username %>](https://github.com/<%= normalUserName%>)<% if (twitter) { %> · Twitter [@<%= twitter %>](https://twitter.com/<%= twitter %>)<% } %>
