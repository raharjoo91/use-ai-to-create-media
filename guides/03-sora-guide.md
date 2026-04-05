# Guide 3: Using Sora for K3 Safety Video Creation

> Generate engaging safety training videos with OpenAI's Sora AI model

## ⚠️ Important Notice

**Sora Availability Status (as of April 2026):**
- Sora is in limited availability
- Access may require waitlist or subscription
- Features and capabilities are evolving
- This guide is based on announced features and best practices

**Always check:** [openai.com/sora](https://openai.com/sora) for current availability and updates

---

## Table of Contents
1. [What is Sora?](#what-is-sora)
2. [Getting Started](#getting-started)
3. [Video Types for K3](#video-types-for-k3)
4. [Prompt Engineering for Safety Videos](#prompt-engineering-for-safety-videos)
5. [Step-by-Step Workflows](#step-by-step-workflows)
6. [Integration with Other Tools](#integration-with-other-tools)
7. [Best Practices & Ethics](#best-practices--ethics)

---

## What is Sora?

**Sora** is OpenAI's text-to-video AI model that can:
- Generate realistic videos from text prompts
- Create scenes up to 60 seconds
- Simulate complex motion and physics
- Understand camera positioning and movement

### Why Video for K3?

| Format | Engagement | Retention | Production Time |
|--------|------------|-----------|-----------------|
| Text only | Low | 10% | Fast |
| Static image | Medium | 35% | Medium |
| **Video** | **High** | **95%** | Slow (traditionally) |
| **AI Video** | **High** | **High** | **Fast** |

**Video Works For:**
- Demonstrating procedures
- Showing consequences (safely)
- Building emotional connection
- Reaching diverse literacy levels
- Standardizing training

---

## Getting Started

### Step 1: Access Sora

```
1. Visit openai.com/sora
2. Join waitlist or subscribe
3. Complete safety training
4. Review content policies
5. Start creating
```

### Step 2: Understand Limitations

**Current Limitations (may change):**
- ⏱️ Maximum 60 seconds per video
- 🎬 Limited control over specific actions
- 🔄 Generation takes time (minutes)
- 💰 Cost per video generation
- 📋 Content review required

### Step 3: Plan Your Video

**Pre-Production Checklist:**
```
☐ Define learning objective
☐ Identify target audience
☐ Determine key message
☐ Script the scenario
☐ Plan visual elements
☐ Prepare fallback options
```

---

## Video Types for K3

### Type 1: Procedure Demonstration

**Best for:** Step-by-step safety procedures

**Examples:**
- How to don PPE correctly
- Emergency evacuation route
- Fire extinguisher operation (PASS method)
- Lockout/Tagout procedure
- Hazard reporting process

**Video Structure:**
```
0:00-0:05  | Introduction: "What you'll learn"
0:05-0:35  | Step-by-step demonstration
0:35-0:50  | Common mistakes to avoid
0:50-1:00  | Summary and call to action
```

### Type 2: Scenario-Based Training

**Best for:** Decision-making and judgment

**Examples:**
- Spotting workplace hazards
- Responding to chemical spill
- Identifying ergonomic risks
- De-escalating conflicts
- Medical emergency response

**Video Structure:**
```
0:00-0:10  | Set the scene
0:10-0:30  | Show the scenario
0:30-0:40  | Pause for decision point
0:40-0:50  | Show correct response
0:50-1:00  | Explain why
```

### Type 3: Emotional Impact

**Best for:** Motivation and awareness

**Examples:**
- "Why we wear safety glasses"
- "A family's perspective on safety"
- "The ripple effect of incidents"
- "Your coworkers count on you"

**Video Structure:**
```
0:00-0:15  | Hook: Emotional opening
0:15-0:35  | Story or message
0:35-0:50  | Connection to workplace
0:50-1:00  | Call to action
```

### Type 4: Micro-Learning

**Best for:** Quick tips and reminders

**Examples:**
- "3-point contact" (15 seconds)
- "Lift with your legs" (15 seconds)
- "Check your PPE" (15 seconds)

**Video Structure:**
```
0:00-0:05  | Show the action
0:05-0:10  | Explain the why
0:10-0:15  | Reinforce the message
```

---

## Prompt Engineering for Safety Videos

### Prompt Structure

```
[SCENE] + [ACTION] + [ENVIRONMENT] + [STYLE] + [CAMERA] + [SAFETY]

Example:
"Construction worker in high-visibility vest and hard hat
demonstrating proper ladder safety by maintaining three points of contact
while climbing an extension ladder at outdoor construction site,
professional training video style, steady medium shot,
all safety equipment properly secured"
```

### Effective Prompt Elements

#### 1. Subject Description
```
Good: "Indonesian construction worker, age 35-45,
       wearing orange hard hat, yellow safety vest,
       blue jeans, work boots"

Bad: "Worker"
```

#### 2. Action Sequence
```
Good: "Worker slowly and deliberately places left foot on ladder rung,
       checks stability, transfers weight while maintaining
       three-point contact with both hands and one foot"

Bad: "Worker climbs ladder"
```

#### 3. Environment Details
```
Good: "Brightly lit construction site during morning,
       clean and organized work area, safety barriers visible,
       blue sky with clouds in background"

Bad: "Construction site"
```

#### 4. Style & Mood
```
Good: "Professional corporate training video style,
       clean and bright lighting, calm and confident atmosphere,
       high production value, educational tone"

Bad: "Video"
```

#### 5. Camera Work
```
Good: "Steady medium shot from waist level,
       slight zoom in on hands during key moment,
       professional cinematic quality"

Bad: "Camera view"
```

### Prompt Templates

#### Template 1: PPE Demonstration
```
"[WORKER] wearing [PPE ITEMS] demonstrates [CORRECT METHOD]
for [TASK] at [LOCATION], [TRAINING VIDEO STYLE],
[CAMERA ANGLE], emphasizing [SAFETY POINT]"

Example:
"Experienced welder wearing welding helmet, leather gloves,
and fire-resistant apron demonstrates proper welding position
and ventilation setup in industrial workshop,
professional safety training video, close-up shot on hands,
emphasizing maintaining safe distance from sparks"
```

#### Template 2: Hazard Identification
```
"[WORKER] notices [HAZARD] at [WORKPLACE],
stops work and [CORRECT ACTION],
[TRAINING VIDEO STYLE], [CAMERA WORK],
showing [SAFE OUTCOME]"

Example:
"Laboratory technician in white coat notices
unlabeled chemical container on lab bench,
stops work and labels container with yellow hazard tag,
professional training video, medium shot with zoom,
showing proper hazard identification procedure"
```

#### Template 3: Emergency Response
```
"[WORKER] responds to [EMERGENCY] by [STEPS],
at [LOCATION], [TRAINING VIDEO STYLE],
[CAMERA FOLLOWING ACTION], showing [SAFE RESOLUTION]"

Example:
"Office worker responds to fire alarm by
calmly standing up, pushing chair in, walking to exit,
not using elevator, in modern office building,
emergency training video, steady tracking shot,
showing proper evacuation behavior"
```

---

## Step-by-Step Workflows

### Workflow 1: Single Procedure Video (30 minutes)

**Goal:** 30-second video on proper lifting technique

```
Phase 1: Preparation (10 min)
├─ Script the action
├─ Write detailed prompt
├─ Identify key frames
└─ Plan variations

Phase 2: Generation (15 min)
├─ Enter prompt to Sora
├─ Wait for generation
├─ Review output
├─ Regenerate if needed
└─ Select best version

Phase 3: Post-Processing (5 min)
├─ Add text overlays
├─ Insert captions
├─ Add narration/audio
└─ Final export
```

**Example Prompt:**
```
"Warehouse worker wearing blue uniform and steel-toed boots
demonstrates proper lifting technique by squatting down,
keeping back straight, grasping box with both hands,
lifting with legs while maintaining straight back,
in well-organized warehouse with shelving,
professional safety training video, side view showing posture,
educational and clear presentation"
```

### Workflow 2: Scenario-Based Video (45 minutes)

**Goal:** 60-second video on hazard identification

```
Phase 1: Script & Storyboard (15 min)
├─ Define hazard scenario
├─ Script worker actions
├─ Plan camera angles
├─ Identify decision points
└─ Write narration script

Phase 2: Generate Scenes (20 min)
├─ Scene 1: Worker approaching hazard
├─ Scene 2: Worker noticing issue
├─ Scene 3: Worker taking correct action
├─ Scene 4: Safe outcome
└─ Scene 5: Summary/learning point

Phase 3: Assembly (10 min)
├─ Combine clips in editor
├─ Add transitions
├─ Insert text overlays
├─ Add narration
└─ Export final video
```

### Workflow 3: Video Series (2-3 hours)

**Goal:** Series of 5 micro-learning videos (15 sec each)

**Topics:**
1. Hard hat adjustment
2. Safety glasses positioning
3. Hearing protection insertion
4. High-visibility vest closure
5. Respirator seal check

```
Phase 1: Batch Preparation (30 min)
├─ Write all 5 prompts
├─ Create consistent style guide
├─ Plan visual continuity
└─ Prepare branded elements

Phase 2: Batch Generation (60 min)
├─ Generate all videos
├─ Review for consistency
├─ Regenerate as needed
├─ Select best versions
└─ Organize by topic

Phase 3: Post-Production (60 min)
├─ Add intro/outro cards
├─ Insert company branding
├─ Add consistent narration
├─ Create playlist/menu
└─ Export all formats
```

---

## Integration with Other Tools

### Complete AI Pipeline

```
Step 1: NotebookLM
└─ Research safety procedures
└─ Generate key points
└─ Create FAQ

Step 2: Script Writing
└─ Use NotebookLM output
└─ Write video script
└─ Plan visual scenes

Step 3: Sora Generation
└─ Convert script to prompts
└─ Generate video clips
└─ Review and select

Step 4: Canva Enhancement
└─ Create intro/outro cards
└─ Design text overlays
└─ Add branded elements

Step 5: Assembly
└─ Combine all elements
└─ Add audio/narration
└─ Final export
```

### Audio & Narration

**Options:**
1. **AI Voice:** ElevenLabs, Murf.ai, Play.ht
2. **Human Voice:** Record yourself or hire voice talent
3. **Text-to-Speech:** Built-in tools, free options

**Audio Tips:**
```
☐ Use clear, slow speech
☐ Allow pauses for emphasis
☐ Match tone to content (serious for safety)
☐ Keep language simple (grade 6-8)
☐ Include captions for accessibility
```

---

## Best Practices & Ethics

### Safety Verification

**CRITICAL:** Always verify AI-generated safety procedures

```
Before Using Any Video:
☐ Have safety professional review
☐ Cross-check with official guidelines
☐ Test with small group first
☐ Provide context and disclaimers
☐ Update if procedures change
```

### Content Ethics

```
DO:
✓ Show realistic scenarios
✓ Demonstrate correct procedures
✓ Include diverse workers
✓ Show positive outcomes
✓ Emphasize personal responsibility

DON'T:
✗ Show graphic injuries
✗ Use scare tactics
✗ Stereotype workers
✗ Minimize risks
✗ Override established procedures
```

### Accessibility

```
Video Must Include:
☐ Captions for dialogue/narration
☐ Audio descriptions for visual elements
☐ Text overlays for key points
☐ Playback speed controls
☐ Mobile-friendly format
```

### Cultural Considerations

```
For Indonesian Context:
☐ Include diverse workers (local + international)
☐ Respect local dress norms
☐ Use appropriate language
☐ Consider religious practices
☐ Reflect local workplace conditions
```

---

## Common Issues & Solutions

### Issue 1: Video Doesn't Match Prompt

**Cause:** Prompt too vague or ambiguous
**Solution:**
```
1. Add specific details
2. Break into separate shots
3. Use consistent terminology
4. Reference visual examples
5. Regenerate with refined prompt
```

### Issue 2: Unrealistic Movements

**Cause:** Physics violations or impossible actions
**Solution:**
```
1. Simplify action description
2. Focus on key moments only
3. Use realistic timing
4. Reference actual procedure
5. Consider multiple shorter clips
```

### Issue 3: Safety Equipment Incorrect

**Cause:** AI doesn't know specific PPE requirements
**Solution:**
```
1. Specify exact equipment in prompt
2. Reference safety standards
3. Review frames carefully
4. Have expert verify
5. Add correction overlays if needed
```

### Issue 4: Inconsistent Style

**Cause:** Prompts vary too much
**Solution:**
```
1. Create style template
2. Use consistent descriptors
3. Generate in batches
4. Review as complete set
5. Edit for consistency
```

---

## Evaluation & Testing

### Testing Checklist

```
Content Testing:
☐ Safety procedures are accurate
☐ Information is current
☐ Scenarios are realistic
☐ No misleading information
☐ Appropriate for audience

Technical Testing:
☐ Video plays smoothly
☐ Audio is clear
☐ Captions are accurate
☐ Works on mobile devices
☐ Loads quickly

Effectiveness Testing:
☐ Viewers understand message
☐ Learning objectives met
☐ Retention is good
☐ Behavior changes occur
☐ Feedback is positive
```

### Metrics to Track

```
Immediate:
├─ Views completed
├─ Quiz scores
├─ Feedback ratings
└─ Questions asked

Long-term:
├─ Incident rates
├─ Behavior observations
├─ Refresher requests
└─ Safety culture scores
```

---

## Resources

- [OpenAI Sora](https://openai.com/sora)
- [AI Voice Tools](https://elevenlabs.io)
- [Video Editing](https://www.capcut.com)
- [Captioning](https://www.rev.com)
- [Safety Video Examples](../examples/videos/)

---

*Last updated: 2026-04-05*
