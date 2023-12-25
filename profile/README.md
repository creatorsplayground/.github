# Creator's playground

- Good to see you!
- We can easily create ideas that were only in your imagination.

```mermaid
flowchart TB
  subgraph user[ ]
    direction TB
    creator1([Creator])
    creator2([Creator])
    creator3([Creator])
    subgraph creator1-community[Personal Community]
          direction TB
          creator1-cm([Community])
          creator1-cm-tp1([Topic])
          creator1-cm-tp2([Topic])
          creator1-cm-th1([Thread])
          creator1-cm-th2([Thread])
          creator1-cm-th3([Thread])
          creator1-cm-th4([Thread])
          creator1-cm-tp1---creator1-cm
          creator1-cm-tp2---creator1-cm
          creator1-cm-th1---creator1-cm-tp1
          creator1-cm-th2---creator1-cm-tp1
          creator1-cm-th3---creator1-cm-tp2
          creator1-cm-th4---creator1-cm-tp2
    end
    subgraph creator2-community[Personal Community]
          direction TB
          creator2-cm([Community])
          creator2-cm-tp1([Topic])
          creator2-cm-tp2([Topic])
          creator2-cm-th1([Thread])
          creator2-cm-th2([Thread])
          creator2-cm-th3([Thread])
          creator2-cm-th4([Thread])
          creator2-cm-tp1---creator2-cm
          creator2-cm-tp2---creator2-cm
          creator2-cm-th1---creator2-cm-tp1
          creator2-cm-th2---creator2-cm-tp1
          creator2-cm-th3---creator2-cm-tp2
          creator2-cm-th4---creator2-cm-tp2
    end
    subgraph creator3-community[Personal Community]
          direction TB
          creator3-cm([Community])
          creator3-cm-tp1([Topic])
          creator3-cm-tp2([Topic])
          creator3-cm-th1([Thread])
          creator3-cm-th2([Thread])
          creator3-cm-th3([Thread])
          creator3-cm-th4([Thread])
          creator3-cm-tp1---creator3-cm
          creator3-cm-tp2---creator3-cm
          creator3-cm-th1---creator3-cm-tp1
          creator3-cm-th2---creator3-cm-tp1
          creator3-cm-th3---creator3-cm-tp2
          creator3-cm-th4---creator3-cm-tp2
    end
    creator1-community---creator1
    creator2-community---creator2
    creator3-community---creator3
  end
  
  subgraph public-community[Public Community]
    subgraph pc-1[ ]
          direction TB
          cm1([Community])
          cm1-tp1([Topic])
          cm1-tp2([Topic])
          cm1-th1([Thread])
          cm1-th2([Thread])
          cm1-th3([Thread])
          cm1-th4([Thread])
          cm1---cm1-tp1
          cm1---cm1-tp2
          cm1-tp1---cm1-th1
          cm1-tp1---cm1-th2
          cm1-tp2---cm1-th3
          cm1-tp2---cm1-th4
      end

    subgraph pc-2[ ]
          direction TB
          cm2([Community])
          tp3([Topic])
          tp4([Topic])
          th5([Thread])
          th6([Thread])
          th7([Thread])
          th8([Thread])
          cm2---tp3
          cm2---tp4
          tp3---th5
          tp3---th6
          tp4---th7
          tp4---th8
    end

  end
  creator1---pc-1
  creator2---pc-1
  creator2---pc-2
  creator3---pc-2
```