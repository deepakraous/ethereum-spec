|  **Section** | **Formal Spec** | **Function** | **Explanation** |
|  :------: | ------ | ------ | ------ |
|   2 | (1) σt+1 ≡ Υ(σt, T) | State Transition | The Next State is defined as Ethereum State Transition Function along Current State with new Transactions |
|   | (2) σt+1 ≡ Π(σt, B) | Mining | The Next State is defined as Block Level State function along with Current Block state with new Block among other things |
|   | (3) B ≡ (...,(T0, T1, ...)) | Mining | Block is defined as series of Transactions among other items |
|   | (4) Π(σ, B) ≡ Ω(B, Υ(Υ(σ, T0), T1)...) | Mining | Block Level StateTransition Function is defined as Block Finalization State Transition Function along with this Block and Ethereum State Changes with Current state and Transaction.<br/> |
