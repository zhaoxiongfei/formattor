formattor
=========

node npm formatter pretty-print css, xml, sql, json


Based on jQuery-format by Zach Shelton
http://zachofalltrades.net

Dual licensed under the MIT and GPL licenses:
  http://www.opensource.org/licenses/mit-license.php
  http://www.gnu.org/licenses/gpl.html

## Useage

<pre>npm install formattor</pre>
<pre>
var formattor = require("formattor");
var sql = "select * form table where id=2";
var options = {method: 'sql'};
sql = formattor(sql, options);
//SELECT *
//FROM table
//WHERE id=2
</pre>

### options
  * method `sql`, `xml`, `json`, `css`
