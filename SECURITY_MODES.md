# Shiro's security feature explained

This is a document describing which parts of Shiro's moderation do the security policies affect.

### Invite Links
<table>
  <tr>
    <th>Off</th>
    <td>Filters messages that match <code>discord.gg/</code></td>
  </tr>
  <tr>
    <th>Low</th>
    <td>Filters messages that match the <i>Off</i> policy + <code>discordapp.com/invite/</code></td>
  </tr>
  <tr>
    <th>Medium</th>
    <td>Filters messages that match the <i>Low</i> policy + <code>discord.me/</code>, <code>discord.io/</code>, <code>top.gg/bots/</code>, <code>top.gg/servers/</code></td>
  </tr>
  <tr>
    <th>High</th>
    <td>Filters messages that match the <i>Medium</i> policy + <code>discordservers.com/server/</code>, <code>discords.com/servers/</code>, <code>discord.st/server/</code></td>
  </tr>
</table>

### Word Filter
<table>
  <tr>
    <th>Off and Low</th>
    <td>Filter individual words that match the filtered word</td>
  </tr>
  <tr>
    <th>Medium</th>
    <td>Removes spaces and tries to match the filtered word to the message</td>
  </tr>
  <tr>
    <th>High</th>
    <td>Removes spaces and special characters and tries to match the filtered word to the message</td>
  </tr>
</table>