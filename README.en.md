# Nutrition Science | Adult Obesity Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Obesity (2024 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Obesity (2024 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Overweight/obesity assessment**: BMI calculation and waist measurement to identify obesity level
- **Energy-level management**: 3 energy levels (1400/1600/1800 kcal) for individualized dietary plans
- **Dietary-nutrition principles**: detailed interpretation and practical advice for 6 official principles
- **TCM dietary support**: 5 syndrome patterns plus dietary formulas
- **Regional menus**: 7 regions × 4 seasons × 3 energy levels with complete menus and energy labels
- **Food exchange tables**: 7 food categories for flexible meal planning
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Energy intake | 1400–1800 kcal/day by level | Individualized rather than one-size-fits-all |
| BMI level | Overweight ≥24, obesity ≥28 | BMI = weight(kg)/height(m)² |
| Waist-risk cutoff | Men ≥90 cm, women ≥85 cm | Abdominal obesity carries higher risk |
| Cooking oil | ≤25 g/day | No more than about two tablespoons |
| Salt | <5 g/day | About one beer-bottle cap |
| Exercise | ≥150 min/week moderate intensity | About 30 minutes of brisk walking daily |
| Weight-loss pace | 0.5–1 kg/week | Do not chase speed; steady is better |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~06 | Six dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-07~11 | Appendix knowledge: food choices, exchange tables, menus, etc. | Appendices 1–5 |
| KPK-12~13 | Disease background and TCM understanding | Preface + disease characteristics |
| KPK-14~18 | Integrated Q&A version | Q&A version |

## File Structure

```text
- skill.yaml: Skill configuration
- system_prompt.md: System prompt
- knowledge_base.md: KPK knowledge base with 18 knowledge points
- recipes_data.md: 7 regions and 84 complete menus
- recipes_overview.md: Menu overview and usage guide
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. Obesity diagnosis requires professional evaluation; self-assessment tools are only preliminary screening.
3. If discomfort occurs during weight loss, stop and consult a physician.
4. Food-medicine substances should be used under professional guidance and not taken in excessive amounts.
5. People with hypertension, diabetes, kidney disease, or other underlying conditions should receive professional physician and nutrition guidance.
6. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT
