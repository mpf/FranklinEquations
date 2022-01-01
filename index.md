@def title = "Equation Numbering"

This is an unnumbered equation:

@@no-number
$$ \alpha $$
@@

This is the first numbered equation:

$$ \beta \label{second equation} $$

The reference number to the second equation is \eqref{second equation}, but it should be "(1)".
