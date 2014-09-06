Nomenclature
============

How to name things?


### External data source

#### Access
- `fetch`
- `store`


### Object

#### Construct unique(ish)
Not (easily) reproducible, such as UUIDs, random sequences.
- `new`

#### Construct mutable
- `create`

### Construct immutable
- `cons`

### Access
- `get_[..]`
- `set_[..]`


### Collection

#### Construct mutable
- `create`

### Construct immutable
- `empty`

#### Access K/V (including indexed)
- `get`
- `set`

#### Access set
- `add`
- `remove`
- `is_member`
- `union`
- `diff`

#### Access queue (FIFO)
Which pair is better?
| Pair                 | Pros                         | Cons |
|----------------------|------------------------------|------|
| `enqueue`, `dequeue` | explicit, suggest fair order | long |
| `in`, `out`          | short, intuitive             | _may_ also mean out of order manipulations |

#### Access stack (LIFO)
- `push`
- `pop`

### Traverse sequence
- `iter`
- `map`
- `filter`
- `fold`
