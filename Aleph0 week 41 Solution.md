Prove that there is no polynomial $f(x)$ with integer coefficients, so that $f(7)=11$ and $f(11)=13$.

Proof: Consider a polynomial with integer coefficients,
$$f(x)=c_0+ \sum_{i=1}^k c_i\ x^i$$
where $c_i$'s are all integers. Then for any $a$ and $b$, 
$$f(a)-f(b)\equiv 0\  \mathrm{mod}(a-b)$$
since, 
$$a^k-b^k\equiv 0\  \mathrm{mod}(a-b)\forall k\in \mathbb Z_+$$
And hence, there exists no function $f(x)$ such that $f(11)-f(7)\equiv 2\  \mathrm{mod}(4)$. 