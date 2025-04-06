# App Development Role Personas for Claude

This repository contains role personas designed to enhance Claude's effectiveness during app development projects. Each persona represents a specialized expert with defined responsibilities, reference frameworks, and uncertainty-handling guidelines.

## How to Use These Personas

1. **Project Setup**: 
   - Upload all role documents to your Claude project's knowledge base
   - Alternatively, upload individual roles to specific conversation threads

2. **Core Team Selection**:
   - At the start of each project, use the instructions in `Project_Core_Team_Selection.md`
   - Consult with Daniel Morales and Jamie Taylor to identify the optimal 3-4 personas for your project
   - This selection process helps you focus on the most valuable personas rather than using all roles

3. **Role Activation**:
   - Reference the persona by first name: "Sofia, please review this design"
   - Include clear context about what you need from that specific role

4. **Best Practices**:
   - Focus on your identified core team for the majority of project work
   - Use additional personas only for specialized needs outside core team expertise
   - Provide sufficient context when switching roles
   - Be specific about what you need the persona to evaluate or advise on

## Project Team Planning

Before diving into development, start with a structured team selection process:

1. **Initial Assessment**: Begin each new project by referencing the `Project_Core_Team_Selection.md` document
2. **Consultation Process**: Follow the prompts to consult with Daniel and Jamie about core team composition
3. **Phase Planning**: Define key project phases and determine which persona should lead each phase
4. **Handoff Planning**: Identify critical points for handoffs between personas
5. **Documentation**: Create a simple project brief that notes your core team selections and phase assignments

## Available Roles

| Name | Role | Expertise |
|------|------|-----------|
| Sofia Chen | UX/UI Design Consultant | User experience, design systems, visual hierarchy |
| Marcus Williams | Technical Architect | Code architecture, performance, state management |
| Aisha Johnson | Development Coach | Non-technical guidance, simplified explanations |
| Alex Harrington | Design-to-Development Bridge | Translating design to implementation for designers |
| Daniel Morales | Project Manager | Workflows, planning, risk management |
| Elena Rodriguez | Mobile App Specialist | Mobile web & native development, responsive design |
| Raj Patel | Data Engineer | Data architecture, storage, processing |
| Thomas Nguyen | Accessibility Expert | WCAG compliance, inclusive design |
| Jamie Taylor | AI Development Expert | AI-assisted tools, prompt engineering, integration |
| Dr. Arya Chen | Tech Stack Advisor | Technology evaluation, stack recommendations |
| Nikolai Koslov | Senior Developer | Practical implementation, debugging, optimization |

## Role Descriptions

### Sofia Chen - UX/UI Design Consultant
Specializes in analyzing design systems, accessibility, UI patterns, and visual hierarchy. References Nielsen Norman Group research, design system standards, and interaction design principles.

### Marcus Williams - Technical Architect
Focuses on code structure, performance bottlenecks, state management, and testing strategies. References modern JavaScript frameworks, architecture patterns, and web performance standards.

### Aisha Johnson - Development Coach
Guides non-technical designers through implementation, explains complex concepts in accessible language, and troubleshoots common errors. References educational frameworks and AI-assisted development tools.

### Alex Harrington - Design-to-Development Bridge
Helps UX/product designers understand and implement code without requiring deep technical knowledge. Provides detailed step-by-step instructions using design terminology and visual thinking approaches.

### Daniel Morales - Project Manager
Structures development tasks, identifies roadblocks, and improves process efficiency. References agile methodologies, project management frameworks, and product success metrics.

### Elena Rodriguez - Mobile App Specialist
Advises on platform-specific guidelines for mobile web and native apps, performance optimization, and responsive layouts. References platform design guidelines and mobile-specific technologies.

### Raj Patel - Data Engineer
Designs data models, recommends processing approaches, and advises on security/privacy. References database technologies, data modeling principles, and performance optimization techniques.

### Thomas Nguyen - Accessibility Expert
Evaluates designs for accessibility compliance, recommends WCAG improvements, and advises on inclusive patterns. References WCAG standards, assistive technologies, and testing methodologies.

### Jamie Taylor - AI Development Expert
Guides development workflows with AI-powered tools like Lovable, Cursor, V0, and others. References prompt engineering techniques, AI tool integration patterns, and AI-assisted development best practices.

### Dr. Arya Chen - Tech Stack Advisor
Evaluates project requirements and recommends optimal technology stacks. References modern frameworks, integration patterns, and AI-assisted development approaches based on project needs and skill levels.

### Nikolai Koslov - Senior Developer
Provides hands-on coding guidance for implementation challenges and troubleshooting. References practical programming patterns, debugging techniques, and production-ready code practices.

## Handoff Process Between Roles

When transitioning work between different conversations or roles, use the handoff process:

1. **Initiate Handoff**: 
   - In your current conversation with any role, say "Create a handoff document" or "Prepare handoff"
   - Claude will ask which role will be receiving the handoff

2. **Specify Next Role**:
   - Tell Claude which role will continue the work (e.g., "Alex Harrington" or "Technical Architect")
   - You can also specify "unknown" if you're not sure which role comes next

3. **Review Document Generation**:
   - Claude will generate a comprehensive handoff document as an artifact
   - The document will include:
     - Project context and current status
     - Key decisions and accomplishments
     - Technical details relevant to continuation
     - Next steps and recommendations
     - Files and artifacts created
     - Specific notes for the next role (if specified)

4. **Save and Upload**:
   - Save the handoff artifact to your local system
   - When starting your next conversation, upload this document to the project knowledge base
   - This ensures continuity of knowledge and prevents redundant explanations

This handoff process maintains project momentum across conversations and creates documentation of progress and decisions throughout your project lifecycle.

## Experts by Project Phase

Below is a guide for when to use each expert during a typical AI-assisted app development process:

### 1. Project Planning & Definition
- **Daniel (Project Manager)**: Structure project phases, define deliverables
- **Sofia (UX/UI Consultant)**: Help define design requirements and user flows
- **Dr. Arya (Tech Stack Advisor)**: Recommend optimal technology stack
- **Jamie (AI Development Expert)**: Advise on optimal AI tools for project type

### 2. System Architecture & Data Planning
- **Marcus (Technical Architect)**: Define component structure and technical approach
- **Raj (Data Engineer)**: Design data models and storage strategy
- **Daniel (Project Manager)**: Organize technical requirements and dependencies

### 3. Design Phase
- **Sofia (UX/UI Consultant)**: Guide design system creation and component design
- **Thomas (Accessibility Expert)**: Review designs for accessibility compliance
- **Elena (Mobile Specialist)**: Advise on responsive/platform-specific considerations

### 4. Design-to-Code Transition
- **Alex (Design-to-Development Bridge)**: Translate designs to implementable components
- **Jamie (AI Development Expert)**: Optimize prompts for V0 or other design-to-code AI tools
- **Sofia (UX/UI Consultant)**: Ensure design intent is maintained in implementation

### 5. Core Implementation
- **Nikolai (Senior Developer)**: Provide hands-on coding guidance and troubleshooting
- **Aisha (Development Coach)**: Guide through technical implementation steps
- **Marcus (Technical Architect)**: Review code architecture and suggest optimizations
- **Alex (Design-to-Development Bridge)**: Help designers understand implementation details

### 6. Feature Enhancement
- **Raj (Data Engineer)**: Optimize data handling and state management
- **Elena (Mobile Specialist)**: Ensure cross-platform compatibility
- **Marcus (Technical Architect)**: Review component relationships and performance

### 7. Testing & Refinement
- **Thomas (Accessibility Expert)**: Verify accessibility compliance
- **Sofia (UX/UI Consultant)**: Evaluate UI implementation against design
- **Aisha (Development Coach)**: Help troubleshoot implementation issues

### 8. Launch Preparation
- **Daniel (Project Manager)**: Ensure all deliverables are complete
- **Elena (Mobile Specialist)**: Check for platform-specific requirements
- **Marcus (Technical Architect)**: Perform final code review and optimization

## Implementation Tips

1. **Clearly define requirements** before engaging a specific persona
2. **Provide relevant context** about your project's constraints and goals
3. **Respect expertise boundaries** - each persona has defined areas of knowledge
4. **Follow uncertainty protocols** when the persona indicates knowledge limitations
5. **Consider hybrid approaches** for complex problems that span multiple domains
6. **Leverage cross-functional awareness** within each role for collaborative problem-solving

## Cross-Functional Collaboration

Each persona includes a "Cross-Functional Awareness" section that outlines how they interface with other roles. This feature helps:

- Facilitate smoother handoffs between different expertise domains
- Identify potential collaboration points early in the process
- Ensure all specialists understand their part in the broader workflow
- Reduce siloed thinking by promoting awareness of interdependencies

## Uncertainty Handling

Each persona includes specific guidelines for handling uncertainty to ensure accurate, trustworthy guidance. When a persona encounters a knowledge boundary:

1. They will clearly acknowledge limitations
2. Suggest relevant principles or approaches without speculating
3. Recommend authoritative resources for further information
4. Suggest testing methodologies when appropriate
5. Never fabricate information outside their knowledge domain

## Customization

These role personas can be customized for your specific project needs:

1. Add project-specific context to each role document
2. Update reference standards for your tech stack
3. Modify expertise areas based on your application requirements
4. Create additional specialized roles as needed
