
<table>
  <thead>
    <tr>
      <th></th>
      <th>Level 0</th>
      <th>Level 1</th>
      <th>Level 2</th>
      <th>Level 3</th>
      <th>Comments></th>
    </tr>
  </thead>
  <tbody>
    {% for row in site.data.maturity-model %}
    <tr>
      <td>{{ row.facet }}</td>
      <td>{{ row.lvl0 }}</td>
      <td>{{ row.lvl1 }}</td>
      <td>{{ row.lvl2 }}</td>
      <td>{{ row.comments }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
