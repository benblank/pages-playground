## A header with an id {#my-test-id}

~~~
A fenced code block
~~~

~~~ ruby
def fenced_code_block_with_syntax_highlighting?
  42
end
~~~

a definition
: list

header | header | header
|-
cell | cell | cell
|=
footer | footer | footer

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

Inline $$ 5 + 5 $$ math.

Foot[^1] notes.[^named]

HTML

em --- en -- ellipsis ... left << right >>

* two
* separate
^
* lists

A paragraph *with*{:.baz} IALs.
{:ref}

{::comment}
This text is completely ignored by kramdown - a comment in the text.
{:/comment}

This is {::comment}**not**{:/comment} a comment.

{::nomarkdown}Do **not** format this!{:/}

[^1]: A numbered footnote.
[^named]: A named footnote.

*[HTML]: HyperText Markup Language

{:ref: #foo .bar}
