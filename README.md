# ThoughtDialog
Automated dialog of thoughts and resulting conclusions.

## History

Chronologically, the idea for ThoughtDialog came second after Urarun (created around 2007) at around 2012 - 2014, before Hans the Organizator in 2015.  I didn't have any thoughts to record but was envisioning a system where one could record thoughts for later collaborative evaluation.  The idea continued to evolve driven by allowing to build on previous thoughts, reusing the facts and logic that still apply and build new thought chains.

## Principles based thinking

Using ThoughtDialog for NLNM is about focusing on NLNM principles to drive the thought process.  The intent is to continuously generate conclusions on the current/local simulation state of NLNM compliance and if necessary present a corrective course of action to the unit commanders.  The needed end effect is collectively executed augmentative measures, that do not impact the tactical goals of the unit and additional systems will have to be developed to implement that.

However, simply alerting a combatant may be insufficient and proactive action may be needed.  If the surrounding/physical situation will lead to a severe shoulder or arm injury immediate action will have to be taken.  Alike scenarios are likely possible in more complex command and control situations - this is to be researched with gathered simulation data.

Another research topic is proactive external communication.  It makes sense to call for a medic or to evacuate an unconscious combatant but ultimately action is only warranted if the current course of action can endanger life, physical wholeness or can lead to a serious/heavy injury - if it violates the Alive, Whole and Undamaged principles (AWU).

## Rules and Determinism

The two key features of ThoughtDialog (revealed by NLNM requirements and thinking about beating terminators) is being rules based and fully deterministic.  Focusing on its core task is also required for successful implementation - ThoughtDialog is to follow NLNM regulations and not to be concerned with tactical objectives or the physical state of the troops beyond AWU.

Each Leaf node will individually generate event-based thoughts.  Multiple Leaf nodes together will create collaborative thought dialogs and hierarchically generate dialog-based conclusions.  As is apparent now the process must be fully deterministic. When all simulation events are replayed in the same order and hierarchy level, the same exact thoughts, dialogs and conclusions must be generated, in the same order and quantity.

The rules based nature of ThoughtDialog is what will enable its real-time determinism, because battlefield events within a unit will come in slower than the deterministic NLNM-regulation-tree-based processing engine will create logical chains and arrive at structured and classified thoughts.  Taking a set of structured thoughts as input along with other existing data will be just as fast given tree data structure application.  Additional techniques to ensure determinism will have to be developed, like proposing thoughts in a Leaf loop order and concluded by the commander's Leaf node when applicable.

## Looking forward

Iteratively and with analysis and design concurrent thought loops, Peace Pipe requests, thought creation triggers and thought deactivation will be developed.   Problems and solutions will start to reveal themselves as the data input and additional needed sub-systems are implemented and real scenarios present themselves.

## Getting it perfected

Very importantly, once properly tested the NLNM regulation tree (Mark Down) must be published and reviewed by observers to spot any incorrect assumptions or logic.  Manual debugging of decision making in replayed simulations must be possible.  Perfecting the engine will come down to continuously iterating on the engine and applying it in additional simulation runs.  Large scale and frequent participation in simulations will be needed to prove its effectiveness.
