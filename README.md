# Win32PrioritySeparation (CS2 Results)

## Overview
I tested Win32PrioritySeparation in Counter-Strike 2 to check if it actually improves FPS or smoothness.  
There are many claims about higher FPS and lower input lag, so this was tested properly under controlled conditions.

---

## Test Setup
- Same map, same settings, same config every run  
- 2 warm-up runs before recording (for proper caching)  
- Multiple recorded runs per setting  

---

## Metrics Tracked
- Average FPS  
- P1 
- 1% Lows

---

## Results
- No consistent improvement observed  
- FPS sometimes slightly higher, sometimes lower, mostly unchanged  
- Frametime behavior remained the same  

---

## Notes on Variance
Small FPS differences are **not caused by the tweak**.  
They are due to:
- Temperature changes  
- Environment variations  
- Normal run-to-run variance  

Repeating the tests the next day produced different results again, confirming this.

---

## Conclusion
- No reliable or repeatable performance benefit  
- No consistent improvement in FPS, 1% lows, or frametime  

If something actually works, it should work every time, not randomly.  
If you cannot reproduce a gain consistently, it is not a real optimization.  

---

## Recommendation
Leave Win32PrioritySeparation at default.
