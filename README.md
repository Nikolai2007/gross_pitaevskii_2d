# gross_pitaevskii_2d
This are the suggestions of the editor:

The authors consider a two-dimensional gas of interacting bosons in the Gross-Pitaevskii limit and prove that, for suitable initial data, its one-body density matrix remains close to a solution of the time-dependent Gross-Pitaevskii equation. While the same problem in three dimensions is by now very well understood, this is to my knowledge the first proof in two-dimensions. Previous work on the static problem in 2d appeared in CMP [23] and similar results for the simpler NLS-limit (softer scaling where correlations are less relevant) appeared in top journals like American Journal of Mathematics [13] and ARMA [6]. This confirms that the 2d problem is not just a simple corollary of the 3d case and also suggests that the new result justifies publication in a top journal like CMP, although the paper is rather long and technical. But that is true for all works on the GP-limit.
The authors apply the general strategy of proof developed by Peter Pickl for the 3d case. The 3d result of Pickl is a very interesting and deep work that, however, did not get as much attention as it presumably deserved. But this is also because the original paper was hard to read and some arguments were merely sketched and not worked out in detail. The new result is thus also a chance to advertise the power of his method once more, this time proving a result that has not been achieved by other methods before.
Unfortunately, the new paper in its current form has again weaknesses in the presen- tation. In my opinion, it is not yet ready for publication and needs a serious revision. While I believe that the highly nontrivial proof is overlall correct, there are several mathematical details that need to be looked at again. Also the presentation needs to be improved in several places, most notably in the introduction. Honestly, in parts the introduyction gives the impression of careless writing and little effort on the side of the authors. Several sentences make no sense if understood literally and need to be correctly interpreted by the reader. As an example take the third sentence of the introduction starting with “Assume that...”. This is a long and complicated paper proving an im- portant result. Therefore it needs and deserves a clear and informative introduction with a well thought out structure. One possibility would be to first fomulate a precise mathamtical statement of what is achieved. At the moment the main theorem appears in Section 2, but it could easily be moved to the first part of the introduction. Then briefly explain how it relates to previous results and why it is difficult. Then collect remarks on the physics.
In the following I first collect some mathematical issues where clarifications or cor- rections are needed. Then I provide a list of comments and suggestions concerning the presentation and end with a list of typos that I found.
My recommendation to the authors is to take care of the mathematical issues and to seriously rework the introduction and other issues of presentation. This could be a really great paper if presented in a clear, concise and careful way. My recommendation to the editors is to accept this paper for publication in CMP once the issues mentioned before and below are taken care off.
Mathematical issues:
• The external field At should be C1 in the time coordinate for any fixed x ∈ R2, otherwise the argument on p. 27 (last line) would not work.
2
• Lemma 4.2(e): to my understanding, one also needs g ∈ L∞(R2) since one uses in the proof that the multiplication operator corresponding to g is a bounded operator. Also, the assumptions on the function h are missing.
• Section 5:
– The authors should state clearly whether the functions jN,R, sR􏰁 and fβ are
defined on R2 or only on BR(0) or BR􏰁(0), respectively. If fβ is to be defined
on R2, one should specify whether it is in C1(R2).
– Is R chosen of order N−β as mentioned in the introduction (p. 5)? –IdonotunderstandwhyIR =0fora=0. Tomyunderstanding,a=0
implies jN,R = 1, hence IR = ∥VN ∥1. baa
• p.27: m􏰂−1−m􏰂 =m􏰂−1−(m(0)−m(1))P0
• Lemma 7.2(b): In the estimate of |hβ1,β(x)|, the estimate for the second sum- mand of hβ1,β (the one with Uβ1,β) is missing. To my understanding, it does not suffice to control only the first summand (with Wβ) since it is not clear whether hβ1,β is non-negative.
• Lemma 7.4: The constant C(m) of the 2d-Sobolev inequality (p. 38, l. 7) is not uniform in m, but the authors choose m = 2p arbitrarily large as part (b) is supposed to hold for any ε > 0. One should therefore prove that C(m) is uniformly bounded as m → ∞. To my understanding, the assertion is however not needed for every ε > 0 but only for a fixed choice of p; in this case, the statement of the lemma could simply be expressed differently.
• Throughout the proof, the authors use the parameters d, ε, η and the parameter β of the potential Mβ. Many estimates are given e.g. for sufficiently large d or sufficiently small ε. However, these parameters are not independent of each other: one needs for instance μ > d, and the parameters appear in different com- binations. In the present formulation, it is hard to see that all requirements can be met simultaneously. The authors should therefore give ranges for the single parameters. This would also solve the problem mentioned above, concerning the choice of ε.
• Proof of Lemma 7.10:
– To my understanding, one only knows that fβ is non-negative (not positive)
and the ground state ΨG is positive only almost everywhere. However, the
argument still works since one knows e.g. that fβ > 0 for x outside suppVN .
– The authors state that Q(ψ) ≥ 0 ∀ψ ∈ H2(R2) implies immediately part (a) for Ψ ∈ H2(R2N ). It is however not necessarily true that the restriction
of a H2(R2N )-function to the submanifold where x2, . . . xN are fixed is in H 2 (R2 ). One could first show the assertion for Ψ ∈ Cc∞ (R2N ) and then
apply a density argument.
– In the proof, Lemma 7.10 is applied to 1B(d) ψ, which is no element of H1(R2) 1
as a consequence of the cutoff 1B(d). However, 1B(d)ψ ∈ D(∇1), hence one 11
should formulate the Lemma for such ψ. This would also avoid the problem mentioned above.
Comments on the presentation:
• The definitions and assumptions on the potentials should be formulated once. Then one can refer to them in the formulation of the theorem. Repeating ev- erything again in the theorem makes the latter much harder to digest. The

formulation of the main theorem should be done with greatest care possible. At the moment it is complicated and sloppy (assumptions on potentials and initial data are not clearly separated, β > 0 appears twice in (a), the regularity as- sumption on φt should be assumed for all t etc.) Moreover, state that also the energies per particle converge. This is an important consequence of the proof that should not be ignored in the statement of the theorem.
• It might also be interesting to state the actual estimate of the rate of the con- vergence of the reduced density matrix.
• I recommend that the authors add a part where they explain the differences between their proof and the 3d case. It would be helpful if they point out which new difficulties arise from the exponential scaling of the interaction and what terms in α and α< must be dealt with differently than in the 3d problem.
• Remark (a) after Theorem 2.1: it would be helpful if the authors could explain where exactly the assumption φt ∈ H 3 (R2 ) for all t > 0 is needed. It might already suffice to refer to the corresponding paragraph on p. 15.
• p. 9 and p. 24, concerning the functional α:
(a) In the proof, the integral version of Gr ̈onwall is used instead of the differ-
ential form.
(b) It is not sufficient that α → 0 implies convergence of the reduced density
matrix but it needs to be equivalent to the convergence of both density matrix and energy per particle.
• It is unclear what is meant by “smoothness properties of Ψt” (p. 25 and p. 28)
• p. 28: It would be interesting to add a reference for ∥φt∥∞ and ∥∇φt∥∞ decaying
as t−1 in the case of no external field.
• Section 6.2.1:
– p. 28: I do not understand the remark in the very last line: also Wβ cannot
be bounded by a polynomial in N−1 for β > 1.
– The authors motivate the construction of the new α using the simpler exam-
ple ⟨⟨ψt, qφt ψt⟩⟩. For this example, I suggest to explain the “replacement” 1
of VN by Mβ in more detail, and in particular to stress that the specific
choice of fβ is crucial for this replacement.
– I further recommend to somewhat motivate the transition from this example
to the real functional α<. In particular, the authors should explain why they use r􏰂 instead of m􏰂 and how the estimate in line 34 relates to the estimate of this new term. This estimate is in fact given later (47) but one should consider mentioning it already there.
• Section 7.1: To my understanding, it is misleading to speak about similar strate- gies when comparing the control of the potentials VN and Wβ. While the former is a quite subtle argument—including the correlations in the description in such a way that VN is replaced by Mβ in the relevant expressions—, the latter is a mere integration by parts, where the potential Uβ is chosen in such a way that hβ1,β = 0 outside the range of the potentials.
• Proof of Lemma 7.2:
(a) One should mention that the solution hβ1,β is unique and equals zero outside
the range of the potentials.
(b) The dy-integrals should be over BRN −β (0). Also, one should mention that
R := diam suppWβ .
3

4
Typos:
• Lemma 7.4(b): In (78) and (79), the more detailed estimate from p. 38 (line 22) is required, hence this should be the statement of the lemma. Formulating the lemma in this way also avoids the assumption that ∥∇1ψ∥ be bounded uniformly in N.
• Lemma 7.9: The lemma combines two statements concerning two different dy- namics, generated by the two very different Hamiltonians HVN and HWβ . The authors should explain the differences between both, either in this section or in the heuristics part in section 3. To my understanding, these differences are mainly the following:
– For Ψt evolving according to Wβ (and with the respective initial data), the expression ∥∇1q1Ψt∥ is small already without the cutoff, hence for this term the choice of d is irrelevant. As it seems, the cutoff is not needed for Wβ and one only formulates the lemma in this way to enable a simultaneous treatment of the respective terms in γb<.
– In contrast, for the dynamics generated by VN, ∥∇1q1Ψt∥ is not small and one needs the cutoff. The respective estimate is more involved than the estimate for Wβ as VN needs to be approximated by the auxiliary potential Mμ. For this, one applies Lemma 7.10, which requires that d > μ.
Besides, I do not see where the estimate of ∥1B(d)∇1q1Ψ∥ enters the proof. It 1
seems to me that the authors need only the estimate of ∥1A(d)∇1q1Ψ∥. 1
• In the proof of Lemma 7.9, the authors use the parameter μ to describe the scaling of the auxiliary potential Mμ, whereas it is called Mβ throughout the rest of the paper. I recommend to exclusively use μ to distinguish this parameter from the scaling of Wβ. This is particularly important because Theorem 2.1 holds for all β > 0 but there are restrictions for μ, e.g. μ > d > 1.
• Lemma 7.11: For completeness, one should also state part (a) with q2p1 instead of q1p2, which is not equivalent to part (a) for Γ = 1B(d) Ψ.
1
 • Theorem2.1(b): V ̸=0andV ≥0. DoesthismeanthatV(x)>0∀x∈R2 or that V must not be identically zero?
• “yield to” instead of “yield” at several points
• p. 7, l. 36: “statisfy”
• p. 10, Notation 4.1(b): “in” missing
• Proof of Lemma 5.5: W instead of M and β1 instead of β at several points
• p. 32, l. 17: “prove”
• p. 38, l. 27: k ̸= j instead of k = 1
• p. 40 (61): wrong sign, and | · | missing
• p. 45, l. 15: there is an exponent (p − 1)/p missing
• p. 57, (112) and the paragraph below: Rβ1
• p. 61: Should this be β > 1?
