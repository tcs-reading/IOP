Interactive Oracle Proofs は Interactive Proofs (IP) と Probabilistic Checkable Proofs (PCP) の両方の一般化となるような証明系である。

## 1. はじめに: IP とは ##
### IP と AM ###
IP は Goldwasser, Micali, and Rackoff によって1989年に考えられた計算量クラスである。
独立に Babai は Arthur--Merlin game を1985年に考案している。これは検証者のメッセージを random bit に限定し、検証者を決定的にした IP である。
k-round の Arthur--Merlin game, AM[k] が AM[2] =: AM に一致することは Babai 自身によって示された。
一方で Goldwasser and Sipser は $$AM[k+2]\supseteq IP[k]$$ という極めて非自明な事実を示し、IP において private random coin が本質的に貢献しないことを明らかにした。
Shamir は Lund, Fortnow, Karloff, and Nisan の ``sumcheck protocol'' を用いて IP[poly(n)] = PSPACE を示した。

### MIP ###
Ben-Or, Goldwasser, Kilian, and Wigderson は証明者を p 人に増やした Multiprover Interactive Proofs (MIP) という証明系を1988年に考案した。
証明者はお互いに通信することが許されず、この制約から soundness が満たされやすくなっており、MIP = NEXP が Babai, Fortnow, and Lund によって 1990年に示された。
証明者が量子エンタングルメントを共有するモデル MIP* は NEXP を含むこと[Ito and Vidick 2012]、証明者が2人で no-signaling 状態を共有するモデルは PSPACE に一致すること[Ito 2010] が知られている。

### PCP ###

### ZK ###

## 2. Interactive Oracle Proofs (IOP) ##

1. Interactive Oracle Proofs, Eli Ben-Sasson, Alessandro Chiesa, and Nicholas Spooner, TCC 2016, <https://eprint.iacr.org/2016/116>
2. Quasilinear-Size Zero Knowledge from Linear-Algebraic PCPs, Eli Ben-Sasson, Alessandro Chiesa, Ariel Gabizon, and Madars Virza, TCC 2016, <https://eprint.iacr.org/2016/021>
3. Short Interactive Oracle Proofs with Constant Query Complexity, Eli Ben-Sasson, Alessandro Chiesa, Ariel Gabizon, Michael Riabzev, and Nicholas Spooner, ICALP 2017, <https://eprint.iacr.org/2016/324>
