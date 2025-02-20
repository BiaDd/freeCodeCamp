---
id: 5900f51f1000cf542c510031
title: 'Завдання 434: жорсткі графи'
challengeType: 1
forumTopicId: 302105
dashedName: problem-434-rigid-graphs
---

# --description--

Пригадайте, що граф — це набір вершин та ребер, які з’єднують ці вершини. Дві вершини, з’єднані ребром, називаються прилеглими.

Graphs can be embedded in Euclidean space by associating each vertex with a point in the Euclidean space.

A flexible graph is an embedding of a graph where it is possible to move one or more vertices continuously so that the distance between at least two nonadjacent vertices is altered while the distances between each pair of adjacent vertices is kept constant.

A rigid graph is an embedding of a graph which is not flexible.

Informally, a graph is rigid if by replacing the vertices with fully rotating hinges and the edges with rods that are unbending and inelastic, no parts of the graph can be moved independently from the rest of the graph.

The grid graphs embedded in the Euclidean plane are not rigid, as the following animation demonstrates:

<img class="img-responsive center-block" alt="animation showing grid graphs are not rigid in Euclidean plane" src="https://cdn.freecodecamp.org/curriculum/project-euler/rigid-graphs-1.gif" style="background-color: white; padding: 10px;" />

However, one can make them rigid by adding diagonal edges to the cells. For example, for the 2x3 grid graph, there are 19 ways to make the graph rigid:

<img class="img-responsive center-block" alt="19 ways to make 2x3 grid graph rigid" src="https://cdn.freecodecamp.org/curriculum/project-euler/rigid-graphs-2.png" style="background-color: white; padding: 10px;" />

Note that for the purposes of this problem, we do not consider changing the orientation of a diagonal edge or adding both diagonal edges to a cell as a different way of making a grid graph rigid.

Let $R(m, n)$ be the number of ways to make the $m × n$ grid graph rigid.

Наприклад, $R(2, 3) = 19$ та $R(5, 5) = 23\\,679\\,901$.

Визначимо $S(N)$ як $\sum R(i, j)$ за умови $1 ≤ i$, $j ≤ N$.

Наприклад, $S(5) = 25\\,021\\,721$.

Знайдіть $S(100)$. Надайте відповідь за модулем $1\\,000\\,000\\,033$.

# --hints--

`rigidGraphs()` має повернути `863253606`.

```js
assert.strictEqual(rigidGraphs(), 863253606);
```

# --seed--

## --seed-contents--

```js
function rigidGraphs() {

  return true;
}

rigidGraphs();
```

# --solutions--

```js
// solution required
```
