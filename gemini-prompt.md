# Gemini Prompt Progressions

---

## I. Initial Prompt – Generic Template

Create a digital art character sprite in an idle standing pose using the following specifications:

- **Hair:** [exact color], [style - bob, ponytail, etc.], [length - shoulder-length]  
- **Face:** [skin tone], [eye color], [nose shape], [facial structure]  
- **Clothing:** [exact items with colors - e.g., "red hoodie with white drawstrings"]  
- **Body:** [height - tall/short/average], [build - slim/stocky], [proportions]  
- **Colors:** [list exact hex codes or color names]  
- **Art style:** [pixel art/cartoon/realistic], [line thickness], [shading style]  
- **Pose:** [pose specifics]  
- **Purpose:** [what is it going to be used for]  

**Example usage:** Arms relaxed at sides, showing full body, facing straight forward, looking into the camera, expression [choose: smiling / neutral / sinister grin], clean sprite style.  
**Note:** Make it suitable for a [2D/3D] game.

---

## II. Secondary Prompt – Same Character (Back View)

Show this exact same character from behind. Back view, facing away from camera. Keep the exact same hair style/color, same clothing details, same body size and proportions. Character in idle standing pose, arms at sides. Use the same digital art style as the reference image.

---

## III. Tertiary Prompt – Character Side

> **Step 1:** Upload the front-facing character image.  

Show this exact same character in side profile facing towards the right of the camera. Keep the exact same hair style/color, same clothing details, same body size and proportions. Standing idle pose with arms at sides. Same art style and colors as the front-facing reference. Profile view showing the character's right side.

---

## IV. Working on Animations  

⚠️ **Create new chats for each generation.**  
**Note:** If the first prompt gives opposite results, just re-prompt while attaching the images. *Low reliability – you may need to repeat uploading and typing in the prompts until you get the desired result.*

---

### A. Front Animation

1. **Upload the front-facing character image**  
   Use this exact same character. Character facing and moving towards viewer. Create a frame of a walking animation for this character.  
   - Left arm at back  
   - Right arm at front  
   - Left foot planting on the ground ahead of the character  
   - Right foot planting on the ground behind the character  
   Same character design as reference image.  

2. **Download the walking frame**  

3. **Upload both idle and walking frames, then prompt:**  
   Use the exact same character. Character facing and moving towards viewer. Complete the walking animation sequence.  
   - Missing frame: right arm at back, left arm at front  
   - Right foot planting on the ground ahead  
   - Left foot planting on the ground behind  
   Same character design as the reference frames.  

---

### B. Back Animation

1. **Upload the back-facing character image**  
   Use this exact same character. Create a frame of a walking animation for this character.  
   - Left arm at back  
   - Right arm at front  
   - Left foot planting on the ground ahead  
   - Right foot planting on the ground behind  
   Same character design as reference image.  

2. **Download the walking frame**  

3. **Upload both back-view idle and walking frames, then prompt:**  
   Use the exact same character. Complete the walking animation sequence.  
   - Missing frame: right arm at back, left arm at front  
   - Right foot planting on the ground ahead  
   - Left foot planting on the ground behind  
   Same character design as the reference frames.  

---

### C. East (Side) Animation

⚠️ **Important:** Sides are the trickiest to work with. Multiple passes may be required since the AI struggles with imagining what’s behind 2D images. You might never be able to correct opposite leg/limb movements.  

1. **Upload the side-facing character image**  
   Create frame 1 of a side-view walking animation. Ensure natural walking motion with opposite limb coordination.  
   - Character facing right  
   - Right arm at front, left arm at back  
   - Left foot planting on the ground ahead  
   - Right foot planting on the ground behind  
   Side profile of same character as reference images.  

2. **Download the walking frame**  

3. **Upload the same image again and reprompt.**  
   Repeat until you get one with opposite limb movements.  

4. **Upload both side-view idle and walking frames, then prompt:**  
   Use the exact same character. Complete the walking animation sequence.  
   - Missing frame: right arm at back, left arm at front  
   - Right foot planting on the ground ahead  
   - Left foot planting on the ground behind  
   Same character design as the reference frames.  
