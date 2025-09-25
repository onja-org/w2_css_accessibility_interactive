# CSS Accessibility Interactive Lab

An interactive learning experience designed to help developers understand keyboard accessibility through hands-on demonstrations and real-world examples.

## 🎯 Overview

This lab provides an immersive way to experience accessibility barriers and solutions firsthand. Instead of just reading about accessibility principles, you'll interact with broken and fixed examples to truly understand the impact of proper keyboard navigation design.

## 🎪 What You'll Experience

### Interactive Demonstrations
- **Real vs Fake Buttons**: Feel the frustration of elements that look clickable but aren't keyboard accessible
- **Focus Indicators**: Navigate "blind" vs with clear visual indicators  
- **Tab Order Chaos**: Experience unpredictable navigation vs logical flow

### Key Learning Areas
- Understanding why keyboard accessibility matters for real users
- Identifying the difference between semantic and non-semantic interactive elements
- Recognizing the importance of visible focus indicators
- Experiencing how broken tab order affects navigation
- Applying keyboard accessibility principles to your projects

## 🌍 Real-World Impact

This lab helps you understand that **16% of the world's population** (over 1 billion people) has some form of disability and might rely on keyboard navigation, including:

- Users with motor disabilities who cannot use a mouse
- Screen reader users who are blind or visually impaired
- People with temporary injuries (broken arm, RSI)
- Power users who prefer keyboard efficiency
- Anyone when their pointing device stops working

## 🚀 Getting Started

1. **Navigate to the lab directory:**
   ```bash
   cd lab/
   ```

2. **Open the interactive experience:**
   - Open `index.html` in your web browser
   - No server setup required - works with file:// URLs

3. **Navigate with keyboard only:**
   - Use `Tab` to move between interactive elements
   - Use `Enter` or `Space` to activate buttons
   - Use arrow keys within dropdowns/select elements
   - Try this throughout the entire lab experience!

## 📁 Lab Structure

```
lab/
├── index.html              # Main interactive lab experience
├── README.md              # Lab-specific instructions
└── demos/                 # Individual demo files
    ├── accessible-button.html
    ├── broken-button.html
    ├── broken-taborder.html
    ├── invisible-focus.html
    ├── logical-taborder.html
    └── visible-focus.html
```

## ⏱️ Time Commitment

**30 minutes** - This is a reading and interaction lab focused on user experience rather than coding.

## 🎓 Learning Outcomes

After completing this lab, you'll:
- Understand the real-world impact of accessibility barriers
- Know how to create truly keyboard-accessible interactive elements
- Recognize the importance of proper focus management
- Be able to test your own projects for keyboard accessibility
- Appreciate why semantic HTML is crucial for inclusive design

## 💡 Key Principles Covered

- **Semantic HTML**: Using proper elements (`<button>` not `<div>`)
- **Focus Management**: Making sure users can see where they are
- **Logical Tab Order**: Navigation that follows visual layout
- **User Empathy**: Understanding real impact on people's lives

## 🌟 Remember

Every user deserves to access and interact with your content. This lab will help you build that understanding through experience, not just theory.
