Workflow Companion
An interactive tool for managing complex creative workflows, designed specifically to accommodate neurodivergent learners.

⚠️ Project Status
This is an educational project in active development. The code was generated through AI collaboration and has not yet been reviewed by a professional developer.

Known Limitations:

Beta quality - may have bugs
Limited browser testing
Basic error handling
Use at your own risk. Always export your data as backup.

If you find issues, please report them!

🎯 What It Does
Interactive checklists with progress tracking across multiple projects
Progressive disclosure - expand details only when you need them
Visual flowcharts showing workflow overview
Searchable content for quick information access
Offline-first - works without internet, no data collection
Multi-project support with export/import for cross-device work
🚀 Try It Now
Live Demo: https://katesartanddesign.github.io/workflow-companion/

No installation needed - just open in your browser!

📚 Current Workflows
FontForge Font Creation - Complete workflow from Illustrator to generated font file
Illustrator setup and SVG export
FontForge import and configuration
Letter sizing and alignment
Spacing and kerning
Validation and troubleshooting
Font generation
Canvas Assignment Management - Track class assignments and deliverables
Planning and requirements gathering
Execution tracking
Review against rubric
Submission checklist
🧠 Why This Exists
As a design student with AuDHD, I struggled with:

Scattered documentation across forums, videos, and tutorials
Losing track of progress through multi-step processes
Cognitive overload from too much information at once
No accommodations for executive function challenges
This tool provides scaffolding that helps students build independence while accommodating different learning styles and cognitive needs.

Key insight: If I'm confused, other students probably are too. This tool makes complex workflows manageable.

🛠️ Built With
Vanilla JavaScript (no frameworks, no dependencies)
LocalStorage for data persistence
CSS custom properties for theming
Template-based architecture for easy expansion
Built through transparent collaboration with Claude AI
Technical approach:

Single HTML file for maximum portability
Offline-first design (works without internet)
Progressive disclosure UI pattern
Modular template system for scalability
📖 Documentation
Process Book - Complete project journey and AI collaboration documentation
Technical Brief - Architecture decisions and developer documentation
Conversation Log - Full dialogue for transparency and verification https://claude.ai/share/f04665e3-e07a-4f6a-8dfb-4ab012d50605
🎓 Educational Principles
This tool embodies established learning theory:

Educational Scaffaching
Provides temporary support structures that fade as learners develop competence:

Breaks complex workflows into manageable steps
Offers detailed guidance when needed
Users gradually internalize the process
Universal Design for Learning (UDL)
Accommodates diverse learners through:

Multiple means of representation (text, flowcharts, progressive disclosure)
Multiple means of engagement (interactive, self-paced)
Multiple means of action/expression (progress tracking, export/import)
Metacognitive Development
Teaches process management, not just tool operation:

Students learn HOW to approach complex tasks
Develops executive function skills
Builds transferable workflow management abilities
🎯 Future Development
Planned workflow templates:

Logo design process
Illustration project workflow
UX design methodology
Print design workflow
Video editing workflow
Planned features:

Template creation UI (no-code template builder)
Template sharing/import system
Due date tracking
Collaboration features
Mobile app version
🤝 Contributing
This is an open educational project. Contributions welcome!

Ways to contribute:

Test with students and provide feedback
Create new workflow templates
Improve code quality or documentation
Translate to other languages
Report bugs or suggest features
To contribute:

Fork this repository
Create a feature branch
Make your changes
Submit a pull request
Or simply open an issue to discuss ideas!

🧪 Testing & Feedback
Current status: In beta testing with design students

Help test this tool:

Try creating a project and working through a workflow
Report any bugs or confusing interfaces
Suggest improvements or additional workflows
Share how it helped (or didn't help) your learning
📬 Contact
Creator: Kate Jensen 
School: University of Colorado Denver 
Email: katesartanddesign@gmail.com
Project Repository: https://github.com/katesartanddesign/workflow-companion

🙏 Acknowledgments
Claude AI (Anthropic) - Technical implementation based on my specifications
Technical consultation - Provided by PARTNERNAME (pending code review)
PROFESSORNAME - Educational guidance and support
Design students - Testing and feedback (names will be added as testing progresses)
📄 License
MIT License - Free to use for educational purposes

Copyright (c) 2026 Kate Jensen

See LICENSE file for full details.

🔧 Technical Details
For developers interested in the architecture:

Data Structure
javascript
{
  projects: [{
    id: "timestamp",
    name: "Project name",
    type: "fontforge" | "canvas",
    progress: {
      "section-item": boolean
    }
  }],
  currentProjectId: "active-id",
  theme: "light" | "dark"
}
Template System
New workflows are added as template objects with sections and items. No code changes required for content updates.

Storage Strategy
LocalStorage for persistence (5-10MB typical limit)
Export/import as JSON for backups and cross-device sync
Architecture designed for easy cloud sync addition
See TECHNICAL-BRIEF.md for complete technical documentation.

📊 Project Stats
Created: January 2026
Status: Beta / Active Development
Users: ADDAFTERTESTING
Workflows: 2 (FontForge, Canvas Assignments)
Lines of Code: ~800 JavaScript, ~600 CSS
💭 Philosophy
Design Principle: Accommodate the user, don't force them to adapt to the tool.

This tool was built by someone with AuDHD, for people with diverse cognitive needs. Every feature decision was made with accessibility and cognitive load in mind.

Core beliefs:

Information should be available when needed, not all at once
Progress tracking reduces anxiety and supports executive function
Different brains need different approaches - provide options
Transparency about AI collaboration models ethical use
Educational tools should teach process, not just content
Last Updated: February 18, 2026
Version: 1.0.0 (Beta)

