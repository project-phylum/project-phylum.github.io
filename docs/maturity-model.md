---
title: Maturity Model

---

# Maturity Model

> A maturity model is a tool that helps people assess the current effectiveness of a person or group and supports figuring out what capabilities they need to acquire next in order to improve their performance.[^1]

In this context, a maturity model provides a self-assessment tool for individuals as they navigate non-monogamous relationships.

## Forming Relationships

<table>
  <thead>
    <tr>
      <th></th>
      <th>Level 0</th>
      <th>Level 1</th>
      <th>Level 2</th>
      <th>Level 3</th>
      <th>Comments</th>
      <th>Tools</th>
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
      <td>
        <ul>
        {% for tool in facet.tools %}
          <li>{{tool}}</li>
        {% endfor %}
        </ul>
      </td>
    </tr>
    {% endfor %}
  </tbody>
</table>

[^1]: https://martinfowler.com/bliki/MaturityModel.html#:~:text=A%20maturity%20model%20is%20a,order%20to%20improve%20their%20performance.
