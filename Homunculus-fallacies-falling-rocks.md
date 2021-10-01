# Homunculus fallacies, falling rocks and the computational paradigm

**also available at:** 
<https://telegra.ph/Homunculus-fallacies-and-falling-rocks-09-24>



There are two different ways a falling rock computes. There are two different homunculus fallacies. And they are all related.


In his [Even beyond Physics: Introducing Multicomputation as a Fourth General Paradigm for Theoretical Science](https://writings.stephenwolfram.com/2021/09/even-beyond-physics-introducing-multicomputation-as-a-fourth-general-paradigm-for-theoretical-science/), Stephen Wolfram proposes the idea that we are about to discover or build towards a 4th paradigm in science. 

The previous three paradigms are, as Stephen writes: 

   * "The first, originating in antiquity, one might call the “structural paradigm”. Its key idea is to think of things in the world as being constructed from some kind of simple-to-describe elements—say geometrical objects—and then to use something like logical reasoning to work out what will happen with them."

   *  The mathematical paradigm: "the idea that things in the world can be described by mathematical equations—and that their behavior can be determined by finding solutions to these equations. [...] In the mathematical paradigm one imagines having a mathematical equation and then separately somehow solving it."

   * The computatonal paradigm: "define a model using computational rules (say, for a cellular automaton) and then explicitly be able to run these to work out their consequences. [...] there may be no faster way to find out what a system will do than just to trace each of its computational steps."

Puting aside the first paradigm (because it is so old and rich and... still alive everywhere), I'd reformulate the mathematical and the computational paradigm as: 

    * The mathematical paradigm: find invariants of the system and then, separately, compute consequences by the way of the human mind

    * The computational paradigm: define the evolution of the system as a computation and then run it, because most of the time there is no faster way.

So, how does a rock fall?  

    * according to the mathematical paradigm: there are invariants of the movement, like the conservation of energy. By knowing the initial condition, we can compute the evolution of the rock (center of mass say) by solving a simple equation. 

    * according to the computational paradigm: the rock is composed by a big number of atoms which interact ones with the others and all interact with the gravitational field. The gravitational field is a property of space and all the interactions can be expressed by simple rules. We build a model of space, the rock and their interactions and then we run it to see how the rock will fall. 

In the case of the rock falling, we can accept that the rock is actually falling as in the computational paradigm, but we do have a much shorter computation to make in the mathematical paradigm, which will give us the way the rock will fall. 

In this simple case the computational paradigm is overkill (although for only slightly more complex systems, as billiards, the computational paradigm does give better results, while the mathematical paradigm let us to solve approximations of the solutions of the mathematical equations which are no longer conserving the important invariants. This is well known by specialists but less known by the general public: it is indeed difficult to make a numerical algorithm for the rigid motion which conserves the invariants of motion. The mathematical paradigm starts to look harder...).

A system which is as physical as the falling rock is a fly's brain. This brings us to the homunculus fallacies.


Dennett introduces the idea of a [Cartesian Theater](https://en.wikipedia.org/wiki/Cartesian_theater), a remnant of the Cartesian dualism: 

"Cartesian materialism is the view that there is a crucial finish line or boundary somewhere in the brain, marking a place where the order of arrival equals the order of "presentation" in experience because what happens there is what you are conscious of. ... Many theorists would insist that they have explicitly rejected such an obviously bad idea. But ... the persuasive imagery of the Cartesian Theater keeps coming back to haunt us—laypeople and scientists alike—even after its ghostly dualism has been denounced and exorcized."


As argued [here](https://github.com/mbuliga/writings/blob/main/gnomon-homunculus.md), there is more here than a homunculus inside our brains, there's also a scenic space which are introduced by the back door in any theory of biological vision which is reducible to a Cartesian theater. (As Phil Agre would say, [there's an orbiculus](https://chorasimilarity.wordpress.com/2021/08/14/phil-agres-orbiculus/).)

The homunculus idea is bad because it leads to infinite application: the homunculus has a homunculus inside. 

This is one homunculus fallacy, which is really hard to avoid. Really hard. 

But there is another homunculus fallacy, less known: in the original homunculus fallacy, the homunculus is inside. In the external homunculus fallacy the homunculus is outside. The fallacy functions as well. 

Let's see an example, [proposed here](https://chorasimilarity.wordpress.com/2013/07/20/on-the-exterior-homunculus-fallacy/). 

In order to understand the biological fly vision, a fly is glued in the center of a huge apparatus, so that the experimenter can control what the fly sees and in the same time it can measure the neural activity of the fly and the movements that the fly makes. 

This is a huge technical achievement, along with the detailed, up to neurons, charting of the fly brain. 

So how does the fly' vision system works? There are two explanations: 

    * the mathematical explanation of the human experimenter. In the explanation is used euclidean geometry and newtonian physics. Some equations are solved.

    * the computational explanation of the fly. There is no place in the fly' brain for euclidean geometry. Something different than what the experimenter tells us happens in the fly brain. It is presumably a local computation with rather simple rules which is done by the fly' brain. Like the computation of the rock when it falls, but in order to reproduce it in the computational model (on a computer) we  probably need a huge computer. 

You may notice that the experimenter' explanation introduces an external homunculus in the theory. The computational explantion is, presently a reasonable hope. 


So the external homunculus fallacy in biological vision is like the mathematical paradigm in science. 

The new science, the 4th paradigm in the making, will attempt to pass beyond or to unify the previous two paradigms. 

But how? 

I don't know yet, however there are clues. One of these clues is that the mathematical paradigm is based on the reasoning with invariants. 

As I argued many times before, like [here for ZSS](https://github.com/mbuliga/zss/blob/master/zss.md), invariants don't compute. Indeed, if we start from the hypothesis that everything is a computation, an invariant is something which does not change during the computation. We can use invariants in order to prove that two computations are the same, or that they are not the same. But we can't compute with invariants, otherwise than separately as in the mathematical paradigm. 

The mathematical paradigm is the mathematical computation based on invariants. Invariants give equations which are left to be solved by the human ingenuity, in order to obtain, hopefully, a shortcut computation which allows us to predict the evolution of the system without running the true computation. 

The computational paradigm concentrates on the true computation and leads us to the realisation of computational irreducibility, namely that more often than not we have to rerun the system' computation in order to understand it. 

Probably the 4th paradigm will help us understand how the two computations -- mathematical and real -- are related. 

And moreover computation is not what it were, in a sense. We understand now, as Stephen Wolfram also writes, that we have somehow to make sense of a computational universe which is decentralized and local. Moreover, we have to discover ways to avoid the external homunculus fallacy or the God's eye point of view and we have to understand  how to reason about [asemantic computing](https://telegra.ph/Asemantic-computing-03-02).


More on this paradigm shift. 


I used to be an admirer of the Erlangen Program and it’s extension to symplectic geometry and Hamiltonian mechanics. I only now realize that the thread which I followed in the last 10 years is an attack on the central dogma of groups, invariants and representations which is pervasive in physics. It was not intended.  Also, now I fully realize that I should assemble notes and publish the role of emergent algebras, or their differential calculus analogs, the dilation structures. That is because it might be a bridge between the two paradigms, showing that the group-invariants-representations dogma of the mathematical paradigm can be worked out as the artificial chemistry of Pure See, from the computational paradigm. I worked on the pieces and I know how they fit and they could go as much as desired, but until now I worked hard to be understood by the computational universe researchers. Or, there is needed a parallel effort in the work in both paradigms. I understand only now why it is objectively hard to make this social effort to work…

Only now I realize the scale of this attack. Put on one side, as a model ToE, the beautiful momentum-map of a symmetry group, with particles as unitary irreps, the legacy of Souriau turned into industry by an army of pragmatic physicists. That would be the magical mathematical recipe of the universe. The cherished epitome of mathematical physics of the 20th century.

On the other side put the many small artificial universes like those of Wolfram, but also Church, Schonfinkel, Turing, Lafont, up to artificial chemistries.

The attack of the mathematical paradigm is to say that the universe can be described by the computational paradigm, embodied by one or any of the universal small universes. That even life at the chemical scale can be explored like this.

The attack is aggravated by the claim that even the mathematical basis of the symmetry groups worship is describable by a particular chemistry of space, embodied by emergent algebras.

What a fight.

What a dirty attack on the most loved scientific discovery, that symmetry groups make invariants and their unitary irreducible representations make the elementary particles.

But each step of the reconstruction of the mathematical paradigm inside the computational one seems accessible. Indeed, complex spaces and their extensions, symplectic manifolds, can be seen as their metric contact structures equivalents. There are intrinsic descriptions in terms of emergent algebras or dilation structures of those, which only little modify the Pure See and the main rewrite, the shuffle. Then the intrinsic differential calculus enters into play in order to define the differential objects; also for the mathematical paradigm is needed only the commutative theory of Lie groups (i.e. with algebras which come from dilations structure which are commutative, namely they respect the shuffle. Unitaries are just differentiable isometries, Hamiltonian systems are just smooth (intrinsically) volume preserving flows, or in particular flows of unitaries, which turn out to have the peculiar property (as seen in the contactification of the symplectic manifold) that the flow lines have Hausdorff measure 2, with density proportional to the Hamiltonian. I have not worked out the full construction of the momentum map in the intrinsic framework, looks to be a very interesting task. But in the end, if it works, we get a fully intrinsic description, only in terms of dilation structures, which itself would be easily (?) turned out into an artificial chemistry a la Pure See. This would show that actually the mathematical paradigm is a collection of particular computations which sit naturally into the computational paradigm.

An institute would be needed for this, or at least time and serenity from my part. But all steps are already available, only the paradigm shift blocks this.


