Meta


^
└── Does negating
a-f
└── Range decider

Character class eg: []
Wildcard eg (.) dot
Quantifiers and greediness eg ?
Alternativon eg (|) and less presidence
Sub-patterns and grouping eg (`()`)
Anchors and Boundaries eg $ ^
Escaping & the backslash

Quantifiers
└── ?
    └── ──── 0 or 1
    +
    └── ──── 1 or more
    *
    └── ──── 0 or more

Ranges calculators
└── {n}
    └── ──── n times
    {n,}
    └────── n or more times
    {n,m}
    └────── between n-m
    {,m}
    └────── not well supported


Quantifier Apply to units
String literal ==> abcd+
Character class ==> [ab]* cd
group ==> a(b|c)? d

Backtracing