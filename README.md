#  Pololu Micro Metal Gearmotor Simulator

A small interactive tool to understand how **Pololu micro metal gear motors** actually behave — not just on paper, but in a more visual and practical way.

Instead of guessing from datasheets, you can tweak inputs and instantly see what happens.

---

##  Why this exists

While working with these motors, I kept running into the same problem:

- Datasheet gives numbers… but not intuition  
- Hard to visualize torque vs speed vs current together  
- Easy to accidentally operate near stall and damage gears  

So I built this to experiment freely before touching real hardware.

---

##  What you can do

Pick a motor:
- LP / MP / HP variants  
- Carbon brush versions (6V / 12V)  
- Gear ratios from **10:1 → 1000:1**

Then play with:
- Voltage  
- PWM  
- Load torque  
- Temperature  

And watch it respond in real time.

---

##  What you’ll see

- Speed (motor + output)
- Current draw  
- Torque  
- Efficiency  
- Power (input/output)

Plus:
- Live **Torque–Speed curve**
- Time-based graphs
- 3D motor visualization

---

##  Useful details

- Uses **actual datasheet values**
- Shows **stall condition clearly**
- Warns when you're exceeding **gearbox torque limits**
- Includes basic **thermal effects (resistance vs temperature)**

---

##  How to run

No setup. No install.

Just open the file:

That’s it.

---

##  Built with

- HTML / CSS / JavaScript  
- Three.js (for 3D view)  
- Chart.js (for graphs)

---

##  Limitations

This is not a perfect physics model:

- Gear losses are simplified  
- No advanced friction modeling  
- Thermal model is basic  

Use it for **understanding and rough estimation**, not final validation.

---

##  Where it helps

- Robotics projects  
- 3D printing mechanisms  
- Gearmotor selection  
- Learning DC motor behavior  

---

##  Future ideas

- Motor driver (H-bridge) simulation  
- Export graph data  
- Better thermal model  
- PID control experiments  

---

##  Author

Vignesh Krishnamurthy

---

If you build something cool using this, I’d genuinely like to see it 🙂
