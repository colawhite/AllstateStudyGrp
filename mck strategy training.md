# MCK Strategy Training
{%hackmd theme-dark %}

The 
```graphviz
digraph {
  compound=true
  rankdir=LR

  graph [ fontname="Source Sans Pro", fontsize=20 ];
  node [ fontname="Source Sans Pro", fontsize=18];
  edge [ fontname="Source Sans Pro", fontsize=12 ];

  subgraph block1 {
    concentrate=true
    a [label="block a"] [shape=box]
    b [label="block b"] [shape=box]
    c [label="block c"] [shape=box]
    a -> b
    a -> c
    a -> d
  }
  

  
}
```



Examples
---
- [this is a test]()
- [Book example](/s/book-example)
- [Slide example](/s/slide-example)
- [YAML metadata](/s/yaml-metadata)
- [Features](/s/features)

Themes
---
- [Dark theme](/theme-dark?both)
- [Vertical alignment](/theme-vertical-writing?both)

###### tags: `Templates` `Book`
