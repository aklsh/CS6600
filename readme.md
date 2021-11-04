# Computer Architecture

Assignments involving modelling and analysis of components of a modern computer, done as a part of a graduate level Computer Architecture Course at IIT Madras (Jul-Nov 2021). 

_This work was done in collaboration with [Arjun](https://github.com/arjunmenonv)._

- [CacheParamEst](https://github.com/aklsh/CacheEval): Reverse Engineering the Block Size and Associativity of L1 Cache of a desktop PC by observing the variation in access latency. 

- [SimCache](https://github.com/aklsh/SimCache): Python-based Simulator of a Uniprocessor cache supporting Direct Mapped, Fully Associative and Set-Associative configurations. Includes implementation of Random, LRU and Pseudo-LRU replacement algorithms.

- [AdapPageManage](https://github.com/aklsh/AdapPageManage): Implementation of Hybrid Row Buffer Management for DRAMs by extending the command scheduler offered by the [USIMM](http://utaharch.blogspot.com/2012/02/usimm.html) DRAM simulator.

- [MMU](https://github.com/aklsh/MMU): Memory Management Unit Simulator in Python implementing multi-level virtual address translation enabling efficient page table management along with LRU replacement for evicting pages and page tables from memory. 

- [Tournament Branch Predictor](https://github.com/aklsh/TournamentBPU): Implementation of the Tournament Branch Predictor, first introduced in the Alpha21264 processor. Uses framework provided by JILP for [CBP2016](https://jilp.org/cbp2016/framework.html) championship.

- [Dynamic Execution Core](https://github.com/aklsh/DynamicExecCore): Python-based simulator for the Dynamic Execution Core of a Superscalar Out-of-Order Processor. Inspired by Tomasulo's Algorithm, this simulator implements register renaming, in-order dispatch and completion of instructions using dispatch, reservation and reorder buffers.
