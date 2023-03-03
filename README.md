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
    C_0(["e53e04ac/base\ne2bddac982e446c64fef1513a9a306edefd508a1"]);
    C_1(["e53e04ac/hold\n8575e49e6bfe80ba61782e3a8f9eb80f78776713"]);
  end;
  subgraph "npmjs";
    C_2(["@types/node\n18.14.5"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  B_0 ----> C_0;
  B_1 ----> C_1;
  B_2 ----> C_2;
  click C_0 "https://github.com/e53e04ac/base/tree/e2bddac982e446c64fef1513a9a306edefd508a1";
  click C_1 "https://github.com/e53e04ac/hold/tree/8575e49e6bfe80ba61782e3a8f9eb80f78776713";
  click C_2 "https://www.npmjs.com/package/@types/node/v/18.14.5";
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
