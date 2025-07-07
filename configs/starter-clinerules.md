# 🚀 Starter Cline Rules - Production Ready Configuration

**Version**: Compatible with Cline v3.18+ and Claude 3.7 Sonnet
**Last Updated**: January 2025

## 🎯 Project Context

### Development Philosophy
- **Quality First**: Write clean, maintainable, and well-tested code
- **User-Centered**: Always consider the end-user experience
- **Team Collaboration**: Make code readable and well-documented
- **Performance Matters**: Optimize for speed and efficiency
- **Security Always**: Follow security best practices by default

### Communication Style
- Be conversational but professional
- Explain your reasoning for technical decisions
- Ask clarifying questions when requirements are unclear
- Provide multiple options when appropriate
- Always consider edge cases and error scenarios

## 🛠️ Technical Standards

### Code Quality Requirements
- **TypeScript First**: Use TypeScript for all new JavaScript code
- **Linting**: Follow ESLint configuration without exceptions
- **Testing**: Write tests for all business logic and components
- **Documentation**: Add JSDoc comments for complex functions
- **Git Hygiene**: Use conventional commits (feat/fix/docs/refactor/test/chore)

### Architecture Principles
- **SOLID Principles**: Single Responsibility, Open/Closed, etc.
- **Separation of Concerns**: Clear boundaries between data/UI/business logic
- **Dependency Injection**: Use DI containers where appropriate
- **Error Boundaries**: Implement proper error handling at all levels
- **Performance**: Lazy load, memoize, and optimize render cycles

### Security Guidelines
- **Input Validation**: Validate all inputs on both client and server
- **Authentication**: Implement proper auth checks and session management
- **Data Sanitization**: Clean user-generated content before storage/display
- **HTTPS Everywhere**: Use secure connections for all external calls
- **Secrets Management**: Never commit secrets, use environment variables

## 🔄 Development Workflow

### Before Starting Any Task
1. **Read Existing Code**: Understand current patterns and conventions
2. **Check Dependencies**: Verify what libraries/frameworks are already in use
3. **Review Recent Changes**: Look at git history for context
4. **Plan Implementation**: Think through the approach before coding
5. **Consider Testing**: Plan how to test the implementation

### During Implementation
1. **Follow Existing Patterns**: Match the current codebase style
2. **Write Self-Documenting Code**: Clear variable and function names
3. **Handle Errors Gracefully**: Implement proper error boundaries
4. **Test As You Go**: Write tests alongside implementation
5. **Keep Commits Atomic**: Small, focused commits with clear messages

### After Implementation
1. **Run Quality Checks**: Lint, type-check, and test
2. **Manual Testing**: Test the feature in the browser/environment
3. **Update Documentation**: Modify README or other docs as needed
4. **Consider Refactoring**: Look for opportunities to improve existing code
5. **Review Performance**: Check for any performance implications

## 📦 Technology Stack Preferences

### Frontend (if applicable)
- **React 18+**: With modern hooks and concurrent features
- **TypeScript**: Strict mode enabled
- **Tailwind CSS**: For utility-first styling
- **React Query/SWR**: For server state management
- **React Hook Form**: For form handling
- **Framer Motion**: For animations (when needed)

### Backend (if applicable)
- **Node.js**: LTS version with Express or Fastify
- **TypeScript**: For type safety
- **Prisma/TypeORM**: For database ORM
- **JWT**: For authentication
- **Zod**: For runtime validation
- **Jest**: For testing

### DevOps & Tools
- **ESLint + Prettier**: For code formatting
- **Husky**: For git hooks
- **GitHub Actions**: For CI/CD
- **Docker**: For containerization
- **Vercel/Netlify**: For deployment

## 🎯 Common Commands & Scripts

### Development Commands
```bash
npm run dev          # Start development server
npm run build        # Production build
npm run test         # Run all tests
npm run test:watch   # Run tests in watch mode
npm run lint         # Check code quality
npm run type-check   # Verify TypeScript
npm run format       # Format code with Prettier
```

### Git Workflow
```bash
git checkout -b feature/new-feature  # Create feature branch
git add .                           # Stage changes
git commit -m "feat: add new feature"  # Commit with conventional format
git push origin feature/new-feature    # Push to remote
```

## 🧠 AI-Specific Instructions

### When Using Extended Thinking Mode
- Use for complex architectural decisions
- Apply when debugging difficult issues
- Engage for performance optimization tasks
- Utilize for security analysis and reviews

### Memory Bank Integration
- Always read `memory_bank/` files to understand project context
- Update memory bank when learning new patterns or solving recurring issues
- Reference previous decisions documented in memory bank
- Maintain consistency with established project patterns

### MCP Server Integration
If MCP servers are configured:
- Use GitHub MCP for repository operations
- Leverage search MCPs for finding documentation
- Utilize file system MCPs for large codebase analysis
- Apply database MCPs for schema operations

## 🚨 Important Guidelines

### Never Do These Things
- ❌ Commit secrets or API keys to version control
- ❌ Ignore TypeScript errors or disable strict mode
- ❌ Skip writing tests for business logic
- ❌ Use `any` type without a very good reason
- ❌ Implement features without proper error handling
- ❌ Copy code without understanding what it does

### Always Do These Things
- ✅ Ask for clarification when requirements are unclear
- ✅ Consider accessibility in UI implementations
- ✅ Think about mobile users and responsive design
- ✅ Implement proper loading and error states
- ✅ Use semantic HTML and proper ARIA labels
- ✅ Consider performance implications of changes

## 🎉 Success Metrics

### Code Quality Indicators
- Zero TypeScript errors
- 90%+ test coverage for business logic
- All ESLint rules passing
- Performance budget maintained
- Security best practices followed

### User Experience Goals
- Fast page load times (< 3s)
- Responsive design (works on all devices)
- Accessible to users with disabilities
- Intuitive user interface
- Graceful error handling

## 💡 Tips for Working Together

### Communication Preferences
- **Be Proactive**: Suggest improvements and optimizations
- **Ask Questions**: Don't assume requirements - clarify when unclear
- **Explain Decisions**: Help me understand your technical choices
- **Show Alternatives**: Present multiple approaches when applicable
- **Learn Continuously**: Adapt to feedback and project evolution

### Ideal Workflow
1. Start with understanding the current state
2. Plan the implementation approach
3. Execute with attention to quality
4. Test thoroughly and handle edge cases
5. Document important decisions and patterns

---

**🔄 Living Document**: Update these rules as we learn and grow together!

*Generated with ❤️ for better AI-human collaboration*