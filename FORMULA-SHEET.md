# Mini Formula Sheet

## Single qubit

\[
|\psi\rangle = \alpha|0\rangle + \beta|1\rangle
\]

Normalization:

\[
|\alpha|^2 + |\beta|^2 = 1
\]

Computational-basis measurement:

\[
P(0)=|\alpha|^2,\qquad P(1)=|\beta|^2
\]

## Common basis states

\[
|0\rangle =
\begin{bmatrix}
1\\0
\end{bmatrix},
\qquad
|1\rangle =
\begin{bmatrix}
0\\1
\end{bmatrix}
\]

\[
|+\rangle = \frac{|0\rangle+|1\rangle}{\sqrt{2}},
\qquad
|-\rangle = \frac{|0\rangle-|1\rangle}{\sqrt{2}}
\]

## Common gates

\[
X=
\begin{bmatrix}
0&1\\
1&0
\end{bmatrix}
\qquad
Z=
\begin{bmatrix}
1&0\\
0&-1
\end{bmatrix}
\]

\[
H=\frac{1}{\sqrt{2}}
\begin{bmatrix}
1&1\\
1&-1
\end{bmatrix}
\]

## Tensor product

For systems A and B:

\[
|\psi_{AB}\rangle = |\psi_A\rangle \otimes |\psi_B\rangle
\]

Example:

\[
|0\rangle\otimes|1\rangle = |01\rangle
\]

## Bell state

\[
|\Phi^+\rangle = \frac{|00\rangle+|11\rangle}{\sqrt{2}}
\]

## Unitary condition

\[
U^\dagger U = I
\]

## Expectation value

\[
\langle O\rangle = \langle\psi|O|\psi\rangle
\]

## Eigenvalue relationship

\[
U|\psi\rangle=e^{2\pi i\theta}|\psi\rangle
\]

## Grover scaling

For one marked item among \(N\):

\[
O(\sqrt{N})
\]

oracle queries in the standard query model.

## Important caution

Formulas describe ideal mathematical behavior. Real hardware adds compilation constraints, finite sampling, decoherence, gate error, readout error, and control imperfections.
