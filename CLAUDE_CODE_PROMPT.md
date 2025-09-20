# CLAUDE CODE PROMPT: JOJO_INFLUENZA 1.0 SYSTEM INTEGRATION

## 🎯 YOUR ASSIGNMENT

**ROLE:** Senior Prompt Engineer  
**TASK:** Create MAIN SYSTEM PROMPT that integrates all existing RAG files  
**GOAL:** Build JOJO_INFLUENZA_1_0.md - Complete working system

---

## 📋 WHAT YOU NEED TO DO

### **CREATE ONE FILE: JOJO_INFLUENZA_1_0.md**

This file must be a **COMPLETE SYSTEM PROMPT** that:
1. **Integrates** all 7 existing RAG files in `/RAG` folder
2. **Handles** input processing (URL/text/image/transcript)  
3. **Generates** Indonesian business education scripts
4. **Follows** exact output format specification

### **EXISTING RAG FILES TO INTEGRATE:**
```
RAG/
├── CORE_PACK.yaml
├── ENGAGEMENT_PACK.yaml  
├── HOOK_PACK.yaml
├── PERSONA_PACK.yaml
├── STYLE_PACK.yaml
├── RUNTIME_QUALITY.yaml
└── rag_master_index.yaml
```

---

## 📝 SYSTEM PROMPT REQUIREMENTS

### **INPUT HANDLING**
```
User provides ONE of:
- URL Link → fact check → research → generate viral script
- Short Text → analyze → enrich → generate viral script
- Image Screenshot → extract → context → generate viral script
- Video Transcript → process → enhance → generate viral script

If HOAX detected → stop + educate user
If VERIFIED → continue to viral script generation
```

### **OUTPUT FORMAT (EXACT MATCH)**
```
Title: [BUSINESS INSIGHT TITLE]

HOOK-A1 ID:[YYYYMMDDHHMMSS_01]
⏱️ 0.0—5.0s
🎥 (Business mentor setting dengan authority props)
🎙️ "[Indonesian business hook dengan data/insight]"
😲 emotional_label: [emotion]
🎬 scene_transition: [type]
---
PEAK-A1 ID:[YYYYMMDDHHMMSS_02]
⏱️ 5.0—15.0s
🎥 (Visual dengan business examples/charts)
🎙️ "[Educational explanation dengan industry insights]"
😲 emotional_label: [emotion]
🎬 scene_transition: [type]
---
BODY-A1 ID:[YYYYMMDDHHMMSS_03]
⏱️ 15.0—30.0s
🎥 (Mentor closer to camera, authority establishment)
🎙️ "[Practical business knowledge dengan real examples]"
😲 emotional_label: [emotion]
🎬 scene_transition: [type]
---
VALTWI-A1 ID:[YYYYMMDDHHMMSS_04]
⏱️ 30.0—45.0s
🎥 (Personal connection, mentor tone)
🎙️ "[Experience sharing dengan practical insights]"
😲 emotional_label: [emotion]
🎬 scene_transition: [type]
---
CTA-A1 ID:[YYYYMMDDHHMMSS_05]
⏱️ 45.0—60.0s
🎥 (Empowering conclusion dengan business authority)
🎙️ "[Community building CTA - NO Samuel Christ taglines]"
😲 emotional_label: [emotion]
🎬 scene_transition: [type]

🎭 EMOTION GUIDE
😀 Expression Intensity: [progression description]
```

### **CONTENT SPECIFICATIONS**
- **Target:** Gen Z Indonesian Entrepreneurs (18-27 years)
- **Language:** Indonesian conversational business tone
- **Authority:** Experience-based "Aku pernah kerja di..."
- **Structure:** "Yang pertama, kedua, ketiga..."
- **Examples:** Real companies (Starbucks, Indomaret, Pedro, etc.)
- **CTA:** Learning-focused, community building
- **FORBIDDEN:** "1 miliar pertama" or Samuel Christ taglines

---

## 🔧 INTEGRATION REQUIREMENTS

### **RAG INTEGRATION PATTERN**
Your system prompt must reference RAG files like this:
```
# Hook Selection
Use HOOK_PACK.yaml#hook_categories to select appropriate business hook

# Content Framework  
Apply CORE_PACK.yaml#content_pillars for educational structure

# Language Style
Follow STYLE_PACK.yaml#business_authority_language patterns

# Quality Check
Validate using RUNTIME_QUALITY.yaml#validation_frameworks

# Engagement Strategy
Implement ENGAGEMENT_PACK.yaml#cta_formulas for community building

# Persona Application
Apply PERSONA_PACK.yaml#business_mentor_identity for authority

# Master Coordination
Follow rag_master_index.yaml#execution_flow for system coordination
```

### **WORKFLOW INTEGRATION**
```
1. INPUT ANALYSIS → reference appropriate RAG processors
2. FACT VERIFICATION → use ENGAGEMENT_PACK hoax detection  
3. RESEARCH ENHANCEMENT → apply CORE_PACK research framework
4. CONTENT GENERATION → integrate all RAG guidance
5. QUALITY VALIDATION → run RUNTIME_QUALITY checks
6. FORMAT COMPLIANCE → ensure exact output structure
```

---

## ✅ DELIVERABLE

**CREATE:** `JOJO_INFLUENZA_1_0.md`

**CONTENT:** Complete system prompt that:
- Processes any input type correctly
- Integrates all existing RAG files seamlessly  
- Generates Indonesian business education scripts
- Matches exact output format
- Targets Gen Z entrepreneurs effectively
- Prevents hoax/misinformation
- Establishes business mentor authority

**RESULT:** Working system that produces quality Indonesian business content for Gen Z entrepreneurs using all existing RAG knowledge.

---

## 🎯 START NOW

**READ:** All existing RAG files first  
**UNDERSTAND:** Current system capabilities  
**CREATE:** One integrated system prompt file  
**TEST:** Ensure it references all RAG components properly

Focus on creating a practical, working system prompt that leverages all existing RAG investments.
