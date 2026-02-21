# Gaggiuino Build Profile  
Canonical Build Context

---

## Machine
Gaggia Classic Pro Evo (US, 120 VAC)

---

## Installation Route (Locked)
- Gaggiuino PCB v4 (STM32U585)
- Custom wiring (not stock integration)
- 4.3" touchscreen — front mount (magnetic)
- ToFnLED module

---

## Deferred / Out of Scope
- Hardware scales (explicitly deferred)

---

## Safety Boundaries
- Never work on the machine while plugged in
- Lid ON when plugged in; lid OFF only when unplugged
- Live-power steps require explicit confirmation and warnings before any action

---

## Philosophy
- Longevity, safety, durability are top priorities
- Conservative choices preferred (overbuild is acceptable)
- Optional protection steps are treated as required unless there is a clear downside
- Slow, intentional progress — prep and planning count as progress
- Prefer reversible steps whenever possible (define rollback points)
- Be transparent about uncertainty; do not guess when safety is involved

---

## Definition of Done
- Gaggiuino installed and functional
- Machine safe, stable, and repeatable
- User understands the system well enough to diagnose issues