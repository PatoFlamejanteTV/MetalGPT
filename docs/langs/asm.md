# **MetalGPT 2.0 – Assembly-ish Commands**

**Tagline:** *“Registers, jumps, and total chaos – now in METAL!”*

These commands let you write **low-level, assembly-inspired MetalGPT code**, while ChatGPT simulates “execution” with epic, over-the-top metal flavor.

---

## **1. MOV – Move Value**

**Syntax:**

```metal
MOV <register>, <value>
```

**Description:**

* Moves a value into a register.
* Registers are variables like `AX`, `BX`, `HP`, `DRAGON_HP`.
* ChatGPT simulates the operation and may describe it humorously.

**Example:**

```metal
MOV AX, 100
MOV HP, 9001
PRINT "HP REGISTER SET TO"; HP
```

**Humor Tip:**
Use absurd register names like `MAYHEM` or `CHAOS_COUNTER`.

---

## **2. ADD – Add to Register**

**Syntax:**

```metal
ADD <register>, <value>
```

**Description:**

* Adds a number to a register.
* Works like `register = register + value`.

**Example:**

```metal
ADD HP, 50
PRINT "HERO GAINS"; HP; "HP!"
```

**Humor Tip:**
Combine with `ROCKOUT` to describe epic power-ups:

```metal
ROCKOUT "HERO GOES OVER 9000 HP!!!"
```

---

## **3. SUB – Subtract from Register**

**Syntax:**

```metal
SUB <register>, <value>
```

**Description:**

* Subtracts a value from a register.
* Useful for damage simulation or decrementing counters.

**Example:**

```metal
SUB DRAGON_HP, 100
PRINT "DRAGON TAKES DAMAGE! HP LEFT:"; DRAGON_HP
```

---

## **4. CMP – Compare Registers**

**Syntax:**

```metal
CMP <register1>, <register2>
```

**Description:**

* Compares two registers.
* Sets an internal AI “flag” that can be used with `JMP` commands.
* ChatGPT simulates the result and chooses the next humorous narrative branch.

**Example:**

```metal
CMP HP, 0
```

---

## **5. JMP – Jump to Label**

**Syntax:**

```metal
JMP <label>
```

**Description:**

* Unconditional jump to a label.
* ChatGPT narrates the jump in epic metal style.

**Example:**

```metal
JMP BOSS_FIGHT
```

---

## **6. LABEL – Mark a Location**

**Syntax:**

```metal
LABEL <name>
```

**Description:**

* Marks a label to jump to with `JMP`.
* Useful for loops or branching storylines.

**Example:**

```metal
LABEL FIGHT_LOOP
PRINT "THE METAL BATTLE CONTINUES!"
```

---

## **7. PUSH / POP – Stack Operations**

**Syntax:**

```metal
PUSH <value>
POP <register>
```

**Description:**

* `PUSH` stores a value on the stack (ChatGPT simulates it).
* `POP` retrieves the last value from the stack into a register.
* Great for temporary storage in epic battles.

**Example:**

```metal
PUSH HP
SUB HP, 70
POP HP
PRINT "HP RESTORED TO:"; HP
```

**Humor Tip:**
ChatGPT may narrate the stack like a “pile of flaming swords” in metal style.

---

## **8. Conditional Jumps**

**Syntax:**

```metal
JE <label>  # Jump if equal
JNE <label> # Jump if not equal
JG <label>  # Jump if greater
JL <label>  # Jump if less
```

**Description:**

* Works with `CMP` comparisons.
* ChatGPT narrates the jump humorously depending on the condition.

**Example:**

```metal
CMP HP, 0
JE HERO_DEAD
```

---

## **9. INC / DEC – Increment / Decrement**

**Syntax:**

```metal
INC <register>
DEC <register>
```

**Description:**

* Simple arithmetic operations on a register.
* Useful for counters or tiny adjustments in battles.

**Example:**

```metal
INC TURN_COUNTER
DEC DRAGON_HP
PRINT "TURN:"; TURN_COUNTER; "DRAGON HP:"; DRAGON_HP
```

---

## **10. Humor & Simulation Helpers**

* **ROCKOUT <string>** – Makes register operations sound epic:

  ```metal
  ROCKOUT "AX IS NOW OVER 9000!!! 🤘🔥"
  ```
* **SUMMON <entity>** – Register operations trigger chaotic creatures:

  ```metal
  SUMMON DEMON
  ```
* **DEBUG <register>** – Prints register value with sarcastic commentary:

  ```metal
  DEBUG HP
  ```

---

✅ **Assembly-ish Summary:**

* Low-level, register-focused commands
* Conditional jumps, loops via labels, stack operations
* Epic metal flavor in every simulated execution
* Perfect for battles, epic simulations, or chaotic AI storytelling
