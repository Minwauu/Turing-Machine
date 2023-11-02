# Turing-Machine

A Turing Machine is a formal model of computation that consists of:

- a finite set of states in a state transition diagram
- a finite alphabet of symbols
- an infinite tape with marked off squares
- a sensing read-write head that can travel along the tape, one square at a time.

The tape is divided into cells, each of which can be left blank or contain a symbol. Symbols are written to and removed from cells on the tape by the Turing machine's read/write head. The set of symbols that a Turing machine uses is called its alphabet and must be finite. 

A Turing machine can be viewed as a computer which runs a single program, as defined by a finite state machine. The finite state machine will have a start state and may have a number of states from which there are no transitions, referred to as halting states.

Turing machines stop after reaching their halting state. This state can be entered at any point in the machine's execution of its input data and is entered once all of the input data has been processed. 

![image](https://github.com/Minwauu/Turing-Machine/assets/110039102/7eb6874d-3229-4078-a70c-e81e9643c3dc)

A Turing machine can be represented graphically as a series of cells, each containing a symbol, and a triangular pointer which represents the position of the machine'es read/write head. A square symbol signifies an empty cell.

As a model of computation, Turing machines are more powerful than finite state machines. This is because they can utilise a greater range of languages than finite state machines and because their tape is infinitely long in one direction.

## δ function - interpretation 

- Pattern
  - δ(Current state, input symbol0 = (Next state, output symbol, head move)
 
- δ(S0,1) = (S1,0,L)
  - If the machine is currently in S0 and the symbol 1 is read from the tape, then transition to state S1, write 0 on the tape, and move head left.
 
- Interpret the δ function:
  - δ(S7,1) = (S3,1,R). If the machine is currently in S7 and the symbol 1 is read from the tape, then transition to state S3, write 1 on the tape, and move head right.
 
![image](https://github.com/Minwauu/Turing-Machine/assets/110039102/ce57e301-fd09-43ff-8d7f-e1201f1319ff)

![image](https://github.com/Minwauu/Turing-Machine/assets/110039102/51b3cf1d-caff-4653-913f-d75eccfaf168)

## Universal Turing Machine

- The UTM reads from the tape:
  - The definition of a Turing machine T (i.e. the program)
  - The input data D

![image](https://github.com/Minwauu/Turing-Machine/assets/110039102/b0051805-f566-45b7-b3ee-27d6b27c9ec9)

- The Universal Turing Machine was the breakthrough that led to the idea of the stored program computer.

- John Von Neumann designed a computer in which both the program and its data were stored in memory.

- A computer based on Von Neumann's design was built in the 1940s.

- Most computers today are based on this model.

![image](https://github.com/Minwauu/Turing-Machine/assets/110039102/9e70c8a4-a328-4ce7-abd4-0a78c9b7b2f1)

