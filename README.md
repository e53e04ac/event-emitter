# event-emitter

~~~~~ sh
npm install e53e04ac/event-emitter
~~~~~

~~~~~ mjs
import { EventEmitter } from 'event-emitter';
~~~~~

~~~~~ mermaid
graph RL;
  A["package.json\npackage-lock.json"];
  subgraph "dependencies";
    B_0(["base"]);
    B_1(["hold"]);
  end;
  subgraph "devDependencies";
    B_2(["@types/node"]);
  end;
  subgraph "github";
    C_0(["e53e04ac/base\ne35c91c119067c191178231a2f7db2a8be9e49fa"]);
    C_1(["e53e04ac/hold\ndb62bd33b4c93d0fb459b06c3b707d82924c6077"]);
  end;
  subgraph "npmjs";
    C_2(["@types/node\n18.14.6"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  B_0 ----> C_0;
  B_1 ----> C_1;
  B_2 ----> C_2;
  click C_0 "https://github.com/e53e04ac/base/tree/e35c91c119067c191178231a2f7db2a8be9e49fa";
  click C_1 "https://github.com/e53e04ac/hold/tree/db62bd33b4c93d0fb459b06c3b707d82924c6077";
  click C_2 "https://www.npmjs.com/package/@types/node/v/18.14.6";
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/event-emitter";
    E_0(["namespace EventEmitter"]);
    E_1(["const EventEmitter"]);
  end;
  M["index.d.ts"]
  subgraph "base";
    I_0_0(["Base"]);
  end;
  subgraph "hold";
    I_1_0(["Get"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  E_0 ----> M;
  E_1 ----> M;
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/event-emitter";
    E_0(["EventEmitter"]);
  end;
  M["index.mjs"]
  subgraph "base";
    I_0_0(["Base"]);
  end;
  subgraph "hold";
    I_1_0(["hold"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  E_0 ----> M;
~~~~~
