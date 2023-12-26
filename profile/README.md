# Creator's playground

- Good to see you!
- We can easily create ideas that were only in your imagination.

```mermaid
flowchart TB
  subgraph users[Users]
    creator1([Creator])
    creator2([Creator])
  end
  subgraph prsnlFrms[Personal Forums]
    subgraph prsnlFrm1[ ]
      direction BT
      prsnlFrm1-frm[[Personal Forum]]
      prsnlFrm1-tpc1((Topic))
      prsnlFrm1-tpc1-thrd1{{Thread}}
      prsnlFrm1-tpc1-thrd2{{Thread}}
      prsnlFrm1-tpc2((Topic))
      prsnlFrm1-tpc2-thrd1{{Thread}}
      prsnlFrm1-tpc2-thrd2{{Thread}}
      prsnlFrm1-frm---prsnlFrm1-tpc1
      prsnlFrm1-frm---prsnlFrm1-tpc2
      prsnlFrm1-tpc1---prsnlFrm1-tpc1-thrd1
      prsnlFrm1-tpc1---prsnlFrm1-tpc1-thrd2
      prsnlFrm1-tpc2---prsnlFrm1-tpc2-thrd1
      prsnlFrm1-tpc2---prsnlFrm1-tpc2-thrd2
    end
    subgraph prsnlFrm2[ ]
      direction BT
      prsnlFrm2-frm[[Personal Forum]]
      prsnlFrm2-tpc1((Topic))
      prsnlFrm2-tpc1-thrd1{{Thread}}
      prsnlFrm2-tpc1-thrd2{{Thread}}
      prsnlFrm2-tpc2((Topic))
      prsnlFrm2-tpc2-thrd1{{Thread}}
      prsnlFrm2-tpc2-thrd2{{Thread}}
      prsnlFrm2-frm---prsnlFrm2-tpc1
      prsnlFrm2-frm---prsnlFrm2-tpc2
      prsnlFrm2-tpc1---prsnlFrm2-tpc1-thrd1
      prsnlFrm2-tpc1---prsnlFrm2-tpc1-thrd2
      prsnlFrm2-tpc2---prsnlFrm2-tpc2-thrd1
      prsnlFrm2-tpc2---prsnlFrm2-tpc2-thrd2
    end
  end
  subgraph shrFrms[Shared Forums]
    subgraph shrFrm1[ ]
      direction TB
      shrFrm1-frm[[Shared Forum]]
      shrFrm1-tpc1((Topic))
      shrFrm1-tpc1-thrd1{{Thread}}
      shrFrm1-tpc1-thrd2{{Thread}}
      shrFrm1-tpc2((Topic))
      shrFrm1-tpc2-thrd1{{Thread}}
      shrFrm1-tpc2-thrd2{{Thread}}
      shrFrm1-frm---shrFrm1-tpc1
      shrFrm1-frm---shrFrm1-tpc2
      shrFrm1-tpc1---shrFrm1-tpc1-thrd1
      shrFrm1-tpc1---shrFrm1-tpc1-thrd2
      shrFrm1-tpc2---shrFrm1-tpc2-thrd1
      shrFrm1-tpc2---shrFrm1-tpc2-thrd2
    end
    subgraph shrFrm2[ ]
      direction TB
      shrFrm2-frm[[Shared Forum]]
      shrFrm2-tpc1((Topic))
      shrFrm2-tpc1-thrd1{{Thread}}
      shrFrm2-tpc1-thrd2{{Thread}}
      shrFrm2-tpc2((Topic))
      shrFrm2-tpc2-thrd1{{Thread}}
      shrFrm2-tpc2-thrd2{{Thread}}
      shrFrm2-frm---shrFrm2-tpc1
      shrFrm2-frm---shrFrm2-tpc2
      shrFrm2-tpc1---shrFrm2-tpc1-thrd1
      shrFrm2-tpc1---shrFrm2-tpc1-thrd2
      shrFrm2-tpc2---shrFrm2-tpc2-thrd1
      shrFrm2-tpc2---shrFrm2-tpc2-thrd2
    end
  end

  prsnlFrm1---creator1
  prsnlFrm2---creator2
  creator1---shrFrm1
  creator1---shrFrm2
  creator2---shrFrm1
  creator2---shrFrm2
```

- Communicate with other creators through the forum.
- You can use your **personal forum** and a **shared forum**.
- **personal forum** is your own space.
- **shared forum** is available to all creators. you can manage **permissions**.

---

