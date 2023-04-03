---
title: Maturity Model

---

<table width="100%">
  <thead>
    <tr>
      <th></th>
      <th>Level 0</th>
      <th>Level 1</th>
      <th>Level 2</th>
      <th>Level 3</th>
      <th>Comments</th>
    </tr>
  </thead>
  <tbody>
    {% for facet in site.data.maturity-model %}
    <tr>
      <td>{{ facet.name }}</td>
      <td>{{ facet.lvl0 }}</td>
      <td>{{ facet.lvl1 }}</td>
      <td>{{ facet.lvl2 }}</td>
      <td>{{ facet.lvl3 }}</td>
      <td>{{ facet.comments }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
