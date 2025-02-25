# Energy usage and cooling

Have you ever felt a computer getting hot in your lap? Did you know that
the electricity bill for a high-end gaming PC can be hundreds of euros per year?

Energy consumption is one of the biggest challenges when designing and
building more and more efficient supercomputers. Also, a large proportion of
the energy used by different components of a computer is converted to heat,
and effort (and possibly energy) is needed also for cooling the supercomputer.
As discussed earlier, main reason for moving into massively parallel computing
(instead of making single CPUs more efficient) was energy consumption. Also,
GPUs are used in supercomputers because they can provide better performance /
energy for certain workloads.

<!-- Data: Energy consumption from living in Finland 2018 66 TWh, number of households 2.7 millions -->
The biggest supercomputer in the world in June 2020, the Japanese Fugaku,
consumes 28 MW of energy, and even though it is within the ten most energy
efficient computers in the world, this energy consumption equals 10 000
average Finnish households. As the importance of energy efficiency is rapidly
increasing, supercomputers are measured not only by their raw computing power,
but also by their energy efficiency in the
[Green 500 list](https://www.top500.org/lists/green500/2020/06/). Concerning
the battle against the global climate change supercomputers are a double-edged
sword, on one hand they help in understanding and fighting the climate change,
on the other hand they use large amounts of energy.

For reference: the heating power of a typical sauna stove is of order of 1 kW.

## Cooling

Due to dense packing of supercomputers, cooling can be more challenging than
with domestic devices. A proper climate can help in cooling, and modern
datacenters have also a lots of infrastructure related to cooling. The two
most common approaches are air-cooling, where a steady air flow is run through
the supercomputer, and liquid cooling, where water (or some suitable liquid)
is circulated through the system.
Often, the waste heat can be used for the warming up the premises close to
datacenter, and in best cases even for close-by municilapities.

Air cooling is relatively simple but not very efficient. Modern densely packed
supercomputers, especially GPU based, require liquid cooling to keep them from
melting down. As a result a datacenter hosting supercomputers needs a massive
and complicated cooling infrastructure with piping, pumps, heat exchangers etc.

In CSC's Kajaani data center LUMI waste heat is going to contribute to the
local municipal household heating.

<!-- Copyright CSC - IT Center for Science Ltd.-->
