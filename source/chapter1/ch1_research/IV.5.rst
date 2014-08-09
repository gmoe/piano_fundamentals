.. _IV.5:

5. Learning Rate Calculation (1000 Times Faster!)
-------------------------------------------------

.. TODO: Use MathJax or similar to replace text math

Here is my attempt to mathematically calculate the piano learning rate of the
methods of this book. The result indicates that it is about 1000 times faster
than the intuitive method. The huge multiple of 1000 makes it unnecessary to
calculate an accurate number in order to show that there is a big difference.
This result appears plausible in view of the fact that many students who worked
hard all their lives using the intuitive method are not able to perform
anything significant, whereas a fortunate student who used the correct learning
methods can become a concert pianist in less than 10 years. It is clear that
the difference in practice methods can make the difference between a lifetime
of frustration and a rewarding career in piano. Now, “1000 times faster” does
not mean that you can become a pianist in a millisecond; all it means is that
the intuitive methods are 1000 times slower than the best methods. The
conclusion we should draw here is that, with the proper methods, our learning
rates should be pretty close to those of the famous composers such as Mozart,
Beethoven, Liszt, and Chopin. Remember that we have certain advantages not
enjoyed by those past “geniuses”. They did not have those wonderful Beethoven
sonatas, Liszt and Chopin etudes, etc., with which to acquire technique, or
those Mozart compositions with which to benefit from the “Mozart effect”, or
books like this one with an organized list of practice methods. Moreover, there
are now hundreds of time-proven methods for using those compositions for
acquiring technique (Beethoven often had difficulty playing his own
compositions because nobody knew the correct or wrong way to practice them). An
intriguing historical aside here is that the only common material available for
practice for all of these great pianists was Bach’s compositions. Thus, we are
led to the idea that studying Bach may be sufficient for acquiring most basic
keyboard skills.

Mathematics is used to solve problems in the following way: First, you must
know the most basic physical law that governs the problem. These laws allow you
to set up what are called differential equations; these are mathematical
statements of the problem. Once the differential equations are set up,
mathematics provides methods for solving them to produce a function which
describes the answers to the problems in terms of parameters that determine
these answers. The solutions to the problems can then be calculated by
inserting the appropriate parameter values into the function.

The physical principle we use to derive our learning equation is the linearity
with time. Such an abstract concept may seem to have nothing to do with piano
and is certainly non-biological, but it turns out that, that is exactly what we
need. So let me explain the concept of “the linearity with time”. It simply
means proportional to time. Learning is analogous to earning money; the
important factor is not the income, but the earnings – how much of the income
you retain. Thus, assuming a certain amount of learning, we need to calculate
how much of that we retain. Linearity with time means that if we forget a
fraction F in a time interval T, we will forget the same fraction F in another
time interval T. Of course, we know that learning is highly non-linear. If we
practice the same short segment for 4 hours, we are likely to gain a lot more
during the first 30 minutes than during the last 30 minutes, and how much we
learn or retain depends wildly on how we do it. However, we are talking about
an optimized practice session averaged over many practice sessions that are
conducted over time intervals of years (in an optimized practice session, we
are not going to practice the same 4 notes for 4 hours!). If we average over
all of these learning processes, they tend to be quite linear. Certainly within
a factor of 2 or 3, linearity is a good approximation, and that amount of
accuracy is all we need. Note that linearity does not depend, to first
approximation, on whether you are a fast learner or a slow learner; this
changes only the proportionality constant. Thus we arrive at the first
equation:

L = kT (Eq. 1.1),

where L is an increment of learning in the time interval T and k is the
proportionality constant. What we are trying to find is the time dependence of
L, or L(t) where t is time (in contrast to T which is an interval of time).
Similarly, L is an increment of learning, but L(t) is a function.

Now comes the first interesting new concept. We have control over L; if we want
2L, we simply practice twice. But that is not the L that we retain because we
lose some L over time after we practice. Unfortunately, the more we know, the
more we can forget; that is, the amount we forget is proportional to the
original amount of knowledge, L(O). Therefore, assuming that we acquired L(O),
the amount of L we lose in T is:

L = -kTL(O) (Eq. 1.2),

where the k’s in equations 1.1 and 1.2 are different, but we will not re-label
them for simplicity. Note that k has a negative sign because we are losing L.
Eq. 1.2 leads to the differential equation

dL(t)/dt = -kL(t) (Eq. 1.3)

where “d” stands for differential (this is all standard calculus), and the
solution to this differential equation is

L(t) = Ke(exp.-kt) (Eq. 1.4),

where “e” is a number called the natural logarithm which satisfies Eq. 1.3, and
K is a new constant related to k (for simplicity, we have ignored another term
in the solution that is unimportant at this stage). Eq. 1.4 tells us that once
we learn L, we will immediately start to forget it exponentially with time if
the forgetting process is linear with time.

Since the exponent is a number, k in Eq. 1.4 has the units of 1/time. We shall
set k = 1/T(k) where T(k) is called the characteristic time. Here, k refers to
a specific learning/forgetting process. When we learn piano, we learn via a
myriad of processes, most of which are not well understood. Therefore,
determining accurate values for T(k) for each process is generally not
possible, so in the numerical calculations, we will have to make some
“intelligent guesses”. In piano practice, we must repeat difficult material
many times before we can play them well, and we need to assign a number (say,
“i”) to each practice repetition. Then Eq. 1.4 becomes

L(i,t,k) = K(i)e(expt.-t[i]/T[k]) (Eq. 1.5),

for each repetition i and learning/forgetting process k. Let’s apply this to a
relevant example. Suppose that you are practicing 4 parallel set (PS) notes in
succession, playing rapidly and switching hands, etc., for 10 minutes. We
assign i = 0 to one PS execution, which may take only about half a second. You
might repeat this 10 or 100 times during the practice session. You have learned
L(0) after the first PS. But what we need to calculate is the amount of L(0)
that we retain after the 10 minute practice session. In fact, because we repeat
many times, we must calculate the cumulative learning from all of them.
According to Eq. 1.5, this cumulative effect is given by summing the L’s over
all the PS repetitions:

L(Total) = Sum(over i)K(i)e(expt.-t[i]/T[k]) (Eq.1.6).

Now let’s put in some numbers into Eq. 1.6 in order to get some answers. Take a
passage that you can play slowly, HT, in about 100 seconds (intuitive method).
This passage may contain 2 or 3 PSs that are difficult and that you can play
rapidly in less than a second, so that you can repeat them over 100 times in
those 100 seconds (method of this book). Typically, these 2 or 3 difficult
spots are the only ones holding you back, so if you can play them well, you can
play the entire passage at speed. Of course, even with the intuitive method,
you will repeat it many times, but let’s compare the difference in learning for
each 100 second repetition. For this quick learning process, our tendency to
“lose it” is also fast, so we can pick a “forgetting time constant” of around
30 seconds; that is, every 30 seconds, you end up forgetting almost 30% of what
you learned from one repetition. Note that you never forget everything even
after a long time because the forgetting process is exponential -- exponential
decays never reach zero. Also, you can make many repetitions in a short time
for PSs, so these learning events can pile up quickly. This forgetting time
constant of 30 seconds depends on the mechanism of learning/forgetting, and I
have chosen a relatively short one for rapid repetitions; we shall examine a
much longer one below.

Assuming one PS repetition per second, the learning from the first repetition
is e(expt.- 100/30) = 0.04 (you have 100 seconds to forget the first
repetition), while the last repetition gives e(expt.-1/30) = 0.97, and the
average learning is somewhere in between, about 0.4 (we don’t have to be exact,
as we shall see), and with over 100 repetitions, we have over 40 units of
learning for the use of PSs. For the intuitive method, we have a single
repetition or e(expt. -100/30) = 0.04. The difference is a factor of 40/0.04 =
1,000! With such a large difference factor, we do not need much accuracy to
demonstrate that there is a big difference.

The 30 second time constant used above was for a “fast” learning process, such
as that associated with learning during a single practice session. There are
many others, such as technique acquisition by PPI (post practice improvement).
After any rigorous conditioning, your technique will improve by PPI for a week
or more. The rate of forgetting, or technique loss, for such slow processes is
not 30 seconds, but much longer, probably several weeks. Therefore, in order to
calculate the total difference in learning rates, we must calculate the
difference for all known methods of technique acquisition using the
corresponding time constant, which can vary considerably from method to method.
PPI is largely determined by conditioning, and conditioning is similar to the
PS repetition calculated above. Thus the difference in PPI should also be about
1,000 times.

Once we calculate the most important rates as described above, we can refine
the results by considering other factors that influence the final results.
There are factors that make the methods of this book slower and factors that
make them faster than the calculated rate. For example, it is not possible to
take full advantage of the 1000 times factor, since most “intuitive” students
may already be using some of the ideas of this book. On the other hand, there
are factors that make the intuitive method slower, so that the above “1000
times faster” result could be an under-estimate. The effects of speed walls are
difficult to calculate because speed walls are artificial creations of each
pianist. However, it is clear that they slow down the intuitive method
significantly. These opposing factors (those that make the intuitive method
slower and those that make it faster) probably cancel each other out, so that
our result of 1000 times faster should be approximately valid. These
calculations show that the use of PSs, practicing difficult sections first,
practicing short segments, and getting up to speed quickly, are major factors
that accelerate learning.

Of course, we didn’t need calculus to tell us that the intuitive method is
slower. However, it is gratifying to see that we can numerically calculate a
difference in learning rate, and that the difference is so large.
