# MyRobotLab UI Theme Generation Manual for Claude
## Complete CSS Class Reference & Styling Guide

---

## 📋 Purpose

This manual provides Claude AI with all necessary information to generate a modern, professional dark theme CSS file for **MyRobotLab WebGUI** without affecting any functionality.

**Framework Stack:**
- Bootstrap 3.3.6
- jQuery UI 1.11.4
- Angular 1.5.3
- Custom MRL components

---

## 🎯 Required CSS Selectors to Style

### 1. BOOTSTRAP 3 CORE COMPONENTS

#### Navigation
```css
/* Primary navigation bar */
.navbar
.navbar-default
.navbar-brand
.navbar-nav
.navbar-nav > li > a
.navbar-nav > li > a:hover
.navbar-nav > li > a:focus
.navbar-nav > .active > a
.navbar-toggle
```

#### Panels & Cards
```css
.panel
.panel-default
.panel-primary
.panel-success
.panel-info
.panel-warning
.panel-danger
.panel-heading
.panel-title
.panel-body
.panel-footer
.panel-group
```

#### Buttons
```css
.btn
.btn-default
.btn-primary
.btn-success
.btn-info
.btn-warning
.btn-danger
.btn-link
.btn:hover
.btn:active
.btn:focus
.btn[disabled]
.btn-group
.btn-toolbar
```

#### Forms
```css
.form-control
.form-control:focus
.form-control[disabled]
.form-group
.input-group
.input-group-addon
.input-group-btn
select.form-control
textarea.form-control
input[type="text"]
input[type="number"]
input[type="password"]
input[type="email"]
input[type="checkbox"]
input[type="radio"]
.form-control::placeholder
```

#### Tables
```css
.table
.table-striped
.table-striped > tbody > tr:nth-of-type(odd)
.table-striped > tbody > tr:nth-of-type(even)
.table-hover > tbody > tr:hover
.table > thead > tr > th
.table > tbody > tr > td
.table > tfoot > tr > td
.table-bordered
```

#### Modals
```css
.modal
.modal-dialog
.modal-content
.modal-header
.modal-title
.modal-body
.modal-footer
.modal-backdrop
```

#### Dropdowns
```css
.dropdown-menu
.dropdown-menu > li > a
.dropdown-menu > li > a:hover
.dropdown-menu > li > a:focus
.dropdown-menu > .active > a
.dropdown-menu > .disabled > a
.dropdown-toggle
```

#### Alerts
```css
.alert
.alert-success
.alert-info
.alert-warning
.alert-danger
.alert-dismissible
.alert-link
```

#### Progress Bars
```css
.progress
.progress-bar
.progress-bar-success
.progress-bar-info
.progress-bar-warning
.progress-bar-danger
.progress-striped
```

#### Labels & Badges
```css
.label
.label-default
.label-primary
.label-success
.label-info
.label-warning
.label-danger
.badge
```

#### Wells
```css
.well
.well-sm
.well-lg
```

#### Tabs & Navigation
```css
.nav
.nav-tabs
.nav-tabs > li > a
.nav-tabs > li > a:hover
.nav-tabs > li.active > a
.nav-pills
.tab-content
.tab-pane
```

#### Lists
```css
.list-group
.list-group-item
.list-group-item:hover
.list-group-item.active
.list-group-item-heading
.list-group-item-text
```

#### Breadcrumbs & Pagination
```css
.breadcrumb
.breadcrumb > li + li:before
.pagination
.pagination > li > a
.pagination > li > a:hover
.pagination > .active > a
.pager
```

#### Tooltips & Popovers
```css
.tooltip
.tooltip-inner
.tooltip-arrow
.popover
.popover-title
.popover-content
```

---

### 2. JQUERY UI COMPONENTS

```css
/* jQuery UI Widgets */
.ui-widget
.ui-widget-content
.ui-widget-header
.ui-state-default
.ui-state-hover
.ui-state-active
.ui-state-focus
.ui-state-disabled

/* jQuery UI Slider */
.ui-slider
.ui-slider-handle
.ui-slider-range
.ui-slider-horizontal
.ui-slider-vertical

/* jQuery UI Dialogs */
.ui-dialog
.ui-dialog-titlebar
.ui-dialog-content
.ui-dialog-buttonpane

/* jQuery UI Tabs */
.ui-tabs
.ui-tabs-nav
.ui-tabs-panel

/* jQuery UI Accordion */
.ui-accordion
.ui-accordion-header
.ui-accordion-content

/* jQuery UI Buttons */
.ui-button
.ui-button:hover
.ui-button-text
```

---

### 3. MYROBOTLAB CUSTOM CLASSES

#### Layout & Container Classes
```css
.container-fluid
body
#statusDisplay
#newService
#handleOpen
#handleClose
#notification-entries
#mrlNotificationsJewel
#notificationsCountValue
.notification-badge
```

#### MRL-Specific Components
```css
/* Service Panels */
.service-panel
.service-button
.switchesButtons
.dropdownLabel

/* Prevent Drag/Select */
.prevent-drag-select
.preventGuiDragSelect

/* Video Components */
.videoContainer
.videoContent
.videoInfo
.ratio

/* Terminal/Console */
.terminal
#log-console

/* Tables */
.tableController
.tableBasic
.tableLimits
.tableAdvanced
.tableScroll
.tableMic
.tableChat
.tableBottom
.table-header-rotated
.table-header-rotated th.rotate-45
```

#### Servo & Motor Controls
```css
/* Servo GUI Classes */
.servoContent
.servoController
.servoBasic
.servoLimits
.servoAdvanced
.servoPositionArea
.servoBubble
.servoCursor
.servoOutputCursor
.servoPanelRow
.servo-control-position
.servo-position
.servo-move-to-slider
.servo-input-limit
.servo-mixer-name
.servo-mixer-value

/* Rest Position */
.restCursor
.rest-position
.rest-slider
.restLabel
.restLabelLimits

/* Input/Output Colors */
.inputColor
.outputColor
.restColor
.dataColor
.output-limit

/* Servo Buttons */
.btn-input
.btn-output
.btn-rest
.btn-speed

/* Slider Components */
.sliderContainer
.sliderLimits
.sliderPosition
.speedSlider
.autoDisableSlider
.base-slider
.minX-slider
.maxX-slider
.minY-slider
.maxY-slider
.double-slider-container
.styled-slider
.slider-progress

/* Servo Mixer */
.rzMixer
.MixerTop
.MixerRow
.MixerServo
.MixerServoSpeed
.MixerDirectory
.sliderMixer
.restMixer
.poseList
.sequenceContentList
```

#### Settings & Configuration
```css
.settingsbar
.settingsbarBasic
.settingsOpenCV
.servoReferences
.servoFilter
.labelZone
.limitsZone
.verticalSpacerBasic
.verticalSpacerLimits
.verticalSpacerAdvanced
```

#### Labels & Text
```css
.labelItem
.labelRow
.labelColumn1
.labelSection
.bigLabel
.servoBigLabelLimits
.servoBigLabelPosition
.limitNumbersFieldInput
.limitNumbersFieldRest
.limitNumbersFieldOutput
```

#### OpenCV & Camera
```css
.OpenCVStyle
.OpenCVStyle .form-inline
.OpenCVStyle .form-control
.OpenCVStyle .btn
.OpenCVStyle input[type=checkbox]
```

#### InMoov-Specific
```css
.inmoov-menu-button
.inMoovButton
.GuiDisplays
.homeGuiButtons
.languageGuiButtons
.helpGuiButtons
.inmoov-sub-panel
```

#### Buttons & Controls
```css
.smallbuttons
.basicStopButton
.basicSpeedLabel
.basicSpeedValue
.updownButton
.lockInputOutputButton
.addPoseButton
.btnServomixer

/* Load/Save */
.loadPose
.savePose
.fieldSave
.fieldDelay
.directoryName
.poseName

/* Status */
.Attached
.Detached
```

#### Chat & ProgramAB
```css
.chatBalloonBot
.chatBalloonUser
.chatBalloonBotLast
.chatContent
.programABstatusBalloon
.tableProgramABtop
.tableProgramABinfo
.tableProgramABBottom
.editAIML
.typeHereField
.userField
.typeField
.typeFolderField
.shortDescription
#buttonMoreInfo
#buttonHideInfo
#tableProgramABtopContainer
.tablemoreInfo
.tabScroll
.tabContainer
.leftPannel
.rightPannel
.Recognized
```

#### Status & Display
```css
.cellStatustrue
.cellStatusfalse
.cellStatusUser
.cellStatusRobot
.cellStatusRecognized
.recordingStatus
.progressText
.nav-color
.nav-icon
.odd
.even
```

#### Misc Utility Classes
```css
.iconsUi
.dividerGray
.item-row
.align-right
.align-middle
.center
.vcenter
.flexrow
.lastColumn
.nowrap1
.cellPadding
.marginBottom
.leftBorder
.servoLineDivider
.valuesRow
.buttonsTable
.buttonsRow
.columns
.width100pct
.not-installed
.photo
.currentPose
.gotoRestButton
.sweep
```

#### Drag/Resize Handles
```css
#dragbar
#ghostbar
#ghostbarTouch
#ghostbarTouchHandler
#bottomMessages
#handleOpenBottomMessages
#handleCloseBottomMessages
```

#### Notifications
```css
#notificationContainer
.fullscreen
.absolute
.modal-custom-lg
.modal-custom-lg .modal-dialog
.modal-custom-lg .modal-content
```

#### Misc IDs
```css
#PinEnable
#PinEnable input
#PinEnable input.form-control[disabled]
#servoContent
#servoContent label span
#servoContent .btn:focus
#controllersToAttach
#outputMinValue
#outputMaxValue
#right
#wrapper
#table-wrapper
#table-scroll
#log-console
```

#### Special States & Colors
```css
.gray1
.gray2
.red
.disabled
[disabled]
.active
:hover
:focus
:active
```

#### Scrollbars
```css
::-webkit-scrollbar
::-webkit-scrollbar-track
::-webkit-scrollbar-thumb
::-webkit-scrollbar-thumb:hover
.tableScroll ::-webkit-scrollbar
.tableScroll ::-webkit-scrollbar-thumb
.OpenCVStyle ::-webkit-scrollbar
.OpenCVStyle ::-webkit-scrollbar-thumb
#tableProgramABtopContainer ::-webkit-scrollbar-thumb
#notificationContainer::-webkit-scrollbar
#notificationContainer::-webkit-scrollbar-thumb
```

#### Text Selection
```css
::selection
::-moz-selection
```

#### Media Queries to Preserve
```css
@media only screen and (max-width: 768px) { }
@media (max-width: 1343px) { }
@media (max-width: 858px) { }
@media (min-width: 1450px) { }
@media (min-width: 700px) { }
```

---

## 🎨 Design Requirements

### Color Palette (Modern Dark Theme)

```css
:root {
    /* Backgrounds */
    --bg-primary: #0d0d0d;      /* Body background */
    --bg-secondary: #1a1a1a;    /* Panels, cards */
    --bg-tertiary: #242424;     /* Headers, elevated */
    --bg-hover: #2a2a2a;        /* Hover states */
    
    /* Borders */
    --border-subtle: #2a2a2a;   /* Default borders */
    --border-medium: #3a3a3a;   /* Hover borders */
    --border-strong: #4a4a4a;   /* Active borders */
    
    /* Text */
    --text-primary: #e0e0e0;    /* Headings */
    --text-secondary: #b8b8b8;  /* Body text */
    --text-muted: #666666;      /* Disabled text */
    --text-placeholder: #555555;/* Placeholders */
    
    /* Actions */
    --color-primary: #4a90e2;   /* Primary action blue */
    --color-primary-hover: #5a9def;
    --color-success: #5cb85c;   /* Success green */
    --color-danger: #d9534f;    /* Danger red */
    --color-warning: #f0ad4e;   /* Warning orange */
    --color-info: #5bc0de;      /* Info cyan */
    
    /* Shadows */
    --shadow-small: 0 2px 4px rgba(0, 0, 0, 0.3);
    --shadow-medium: 0 4px 8px rgba(0, 0, 0, 0.4);
    --shadow-large: 0 8px 16px rgba(0, 0, 0, 0.5);
    
    /* Transitions */
    --transition-fast: 0.15s ease;
    --transition-normal: 0.2s ease;
    --transition-slow: 0.3s ease;
}
```

### Spacing System
```css
/* Use 8px base unit */
4px  (0.25rem)  - tight spacing
8px  (0.5rem)   - default padding
16px (1rem)     - component spacing
24px (1.5rem)   - section spacing
32px (2rem)     - large spacing
```

### Typography
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif;
12px - Small text
14px - Body text (default)
16px - Emphasized
18px - Subheadings
24px - Headings
```

---

## 🔧 Implementation Rules

### 1. Use !important Strategically
Only use `!important` when overriding existing inline styles or framework defaults:
```css
/* Required for Bootstrap overrides */
.panel-default { background: #1a1a1a !important; }
.navbar { background: #1a1a1a !important; }

/* Not needed for new properties */
.custom-class { 
    background: #1a1a1a;  /* No !important needed */
}
```

### 2. Maintain Functionality
- **DO NOT** change `display` properties
- **DO NOT** change `position` properties
- **DO NOT** change `z-index` values
- **DO NOT** modify dimensions unless for minimum sizing
- **ONLY** modify: colors, backgrounds, borders, shadows, transitions

### 3. Preserve Responsive Behavior
Keep all existing media queries and add dark theme colors inside them:
```css
@media only screen and (max-width: 768px) {
    .navbar {
        background: #1a1a1a !important;
        /* Keep existing properties */
    }
}
```

### 4. Handle Special States
```css
/* Always style all states */
.btn {
    background: #2a2a2a;
}
.btn:hover {
    background: #353535;
}
.btn:active {
    background: #404040;
}
.btn:focus {
    outline: 2px solid #4a90e2;
}
.btn[disabled],
.btn.disabled {
    opacity: 0.5;
    cursor: not-allowed;
}
```

### 5. Gradients for Buttons
Use subtle gradients for action buttons:
```css
.btn-primary {
    background: linear-gradient(135deg, #4a90e2, #357abd);
}
```

---

## ⚠️ Critical Requirements

### MUST DO:
1. ✅ Style ALL listed selectors above
2. ✅ Use the exact color palette provided
3. ✅ Include smooth transitions (0.2s ease)
4. ✅ Style hover states for all interactive elements
5. ✅ Make forms clearly distinguishable (borders, backgrounds)
6. ✅ Ensure text is readable (minimum 4.5:1 contrast)
7. ✅ Style scrollbars (webkit-scrollbar)
8. ✅ Include focus indicators for accessibility
9. ✅ Preserve all existing spacing/layout
10. ✅ Test all button sizes (min-height: 36px)

### MUST NOT DO:
1. ❌ Use neon colors (#00ffff, #ff00ff, etc.)
2. ❌ Use pure white (#ffffff) - use #e0e0e0 instead
3. ❌ Add glowing/shadow effects excessively
4. ❌ Change display or positioning properties
5. ❌ Modify z-index values
6. ❌ Break responsive layouts
7. ❌ Add animations longer than 0.3s
8. ❌ Use more than 5 main colors

---

## 📝 Output Format

Generate a complete CSS file with this structure:

```css
/*
 * Modern Dark Theme for MyRobotLab WebGUI
 * Framework: Bootstrap 3.3.6 + jQuery UI 1.11.4 + Angular 1.5.3
 * Generated: [Date]
 */

/* ========== CSS VARIABLES ========== */
:root {
    /* Variables here */
}

/* ========== GLOBAL STYLES ========== */
body { }

/* ========== BOOTSTRAP OVERRIDES ========== */
/* Navigation */
.navbar { }
.navbar-default { }

/* Panels */
.panel { }
.panel-default { }

/* Buttons */
.btn { }
.btn-primary { }

/* Forms */
.form-control { }

/* Tables */
.table { }

/* Modals */
.modal-content { }

/* etc. */

/* ========== JQUERY UI OVERRIDES ========== */
.ui-widget { }
.ui-slider { }

/* ========== MYROBOTLAB CUSTOM COMPONENTS ========== */
/* Servo Controls */
.servoContent { }
.servoBubble { }

/* Video */
.videoContainer { }

/* Terminal */
.terminal { }
#log-console { }

/* etc. */

/* ========== SCROLLBARS ========== */
::-webkit-scrollbar { }

/* ========== UTILITIES ========== */
.disabled { }
::selection { }

/* ========== RESPONSIVE ========== */
@media only screen and (max-width: 768px) { }
```

---

## 🎯 Example Implementation

### Complete Button Styling Example:
```css
/* Standard Button */
.btn,
button {
    background: #2a2a2a !important;
    border: 1px solid #3a3a3a !important;
    color: #e0e0e0 !important;
    padding: 8px 16px !important;
    min-height: 36px !important;
    font-weight: 500 !important;
    border-radius: 4px !important;
    transition: all 0.2s ease !important;
}

.btn:hover,
button:hover {
    background: #353535 !important;
    border-color: #4a4a4a !important;
    transform: translateY(-1px);
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3) !important;
}

.btn:active,
button:active {
    transform: translateY(0) !important;
    box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.3) !important;
}

.btn-primary {
    background: linear-gradient(135deg, #4a90e2, #357abd) !important;
    border: 1px solid #357abd !important;
    color: #ffffff !important;
}

.btn-primary:hover {
    background: linear-gradient(135deg, #5a9def, #4585c7) !important;
}

.btn[disabled],
.btn.disabled {
    opacity: 0.5 !important;
    cursor: not-allowed !important;
}
```

---

## ✅ Final Checklist

Before delivering the CSS file, verify:

- [ ] All Bootstrap 3 components are styled
- [ ] All jQuery UI components are styled
- [ ] All MyRobotLab custom classes are styled
- [ ] Color palette matches exactly
- [ ] All interactive elements have hover states
- [ ] Focus indicators are visible
- [ ] Scrollbars are custom styled
- [ ] Text is readable on dark backgrounds
- [ ] Buttons are properly sized (min 36px height)
- [ ] Forms are clearly distinguishable
- [ ] No neon/glowing effects
- [ ] Transitions are smooth (0.2s)
- [ ] No functionality is broken
- [ ] Responsive breakpoints are preserved
- [ ] File is properly commented
- [ ] CSS is organized logically

---

## 🚀 Prompt to Use

```
Using the MyRobotLab UI Theme Generation Manual, create a complete dark theme CSS file that:

1. Styles all listed Bootstrap 3, jQuery UI, and MyRobotLab custom selectors
2. Uses the exact color palette specified in the manual
3. Maintains all existing functionality (no display/position changes)
4. Includes smooth transitions and hover effects
5. Ensures text readability and accessibility
6. Follows all MUST DO and MUST NOT DO requirements

Generate a production-ready CSS file with proper organization and comments.
```

---

**Version:** 2.0  
**Target Application:** MyRobotLab WebGUI v1.1.1610  
**Last Updated:** 2026-02-17
