# Integration in System Design

A lot of software philosophy does not cover the part where you actually integrate your system. A struggled for a while recognising I can analytically separate concepts and code, but I didn't really get the point that these pieces need to come together to get something done.

Concepts that model the combination of components:
- Controller (MVC)
- Motherbaord (hardware)

At some point you need to think about how components fit together, and make them fit together, accepting the fact the general/reuse aspect goes to zero. Controllers are system use cases, in that they usually serve a particular concrete functional requirement - you cannot reuse them across applications. But they get things done in your application ultimately.
