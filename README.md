# event-emitter

~~~~~ sh
npm install e53e04ac/event-emitter
~~~~~

~~~~~ mjs
import { EventEmitter } from 'e53e04ac/event-emitter';
~~~~~

~~~~~ mermaid
graph RL;
  A(["e53e04ac/event-emitter"]);
  subgraph "dependencies";
    B_0(["e53e04ac/base"]);
    B_1(["e53e04ac/hold"]);
  end;
  subgraph "devDependencies";
    B_2(["@types/node"]);
  end;
  A --reference--> B_0;
  A --reference--> B_1;
  A --reference--> B_2;
  click B_0 "https://github.com/e53e04ac/base/tree/86bc9dc951e32d7e173b8e7bf020b9439d75f8f7";
  click B_1 "https://github.com/e53e04ac/hold/tree/385afd8049a499071f966af24caf970731543db4";
  click B_2 "https://www.npmjs.org/package/@types/node/v/18.13.0";
~~~~~

~~~~~ mermaid
graph LR;
  subgraph "e53e04ac/event-emitter"
    C0("index.mjs");
    C1("index.d.ts");
  end;
  subgraph "base"
    D0(["Base"]);
  end;
  subgraph "hold"
    D1(["hold"]);
    D2(["Get"]);
  end;
  D0 --import--> C0;
  D1 --import--> C0;
  D0 --import--> C1;
  D2 --import--> C1;
~~~~~
