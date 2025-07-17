# Research Prompt Engineer Testing Framework

## Overview

This directory contains the comprehensive testing framework for evaluating the Research Prompt Engineer system's effectiveness, quality, and adherence to specifications. The framework consists of systematic test cases, evaluation protocols, and continuous improvement processes.

## Components

### Evaluator System

**File**: `evaluator_instructions.md`

The Research Prompt Engineer Evaluator is designed to be deployed as a Claude Project, ChatGPT Project, or Gemini Gem to systematically assess:

- **Chat Interactions** - The conversational process between user and Research Prompt Engineer
- **Generated Research Prompts** - The final prompts created for different AI platforms
- **Research Reports** - The outputs produced by AI models using those prompts

#### Key Features

- **Scoring System** with Template Adherence, Research Methodology, and Prompt Quality components
- **5-Point Integer Scale** with clear performance benchmarks
- **Comprehensive Analysis** across multiple evaluation dimensions
- **Actionable Recommendations** for system improvement
- **Comparative Analysis** for evaluating different versions or approaches

### Test Case Framework

**Template**: `test_case_template.md`

Standardized template for creating consistent, comprehensive test cases that evaluate specific system capabilities and user scenarios.

## Test Cases

### TC001: Basic Literature Review ✅

- **File**: `tc001_basic_literature_review.md`
- **Type**: Academic Literature Review
- **Complexity**: Basic to Intermediate
- **Focus**: Template adherence, academic research methodology
- **Status**: Complete

### TC002: Beginner User Experience

- **File**: `tc002_beginner_user.md`
- **Type**: Educational Research
- **Complexity**: Basic
- **Focus**: System accessibility, educational guidance, simplified workflows
- **User Profile**: Undergraduate student, first research project
- **Key Testing**: Socratic questioning effectiveness, hand-holding protocols
- **Status**: Development needed

### TC003: File-Heavy Document Analysis

- **File**: `tc003_file_heavy_analysis.md`
- **Type**: Document Analysis
- **Complexity**: Advanced
- **Focus**: File upload integration, document synthesis, citation management
- **User Profile**: Legal researcher analyzing multiple case files
- **Key Testing**: Multiple file handling, complex synthesis protocols
- **Status**: Development needed

### TC004: Rapid Prototype Research

- **File**: `tc004_rapid_prototype.md`
- **Type**: Quick Background Research
- **Complexity**: Basic
- **Focus**: Time-constrained workflows, efficiency, essential information extraction
- **User Profile**: Consultant needing quick client background (2-hour deadline)
- **Key Testing**: Speed optimization, prioritization protocols
- **Status**: Development needed

### TC005: Complex Multi-Methodology Research

- **File**: `tc005_multi_methodology.md`
- **Type**: Mixed Methods Research
- **Complexity**: Advanced
- **Focus**: Quantitative + qualitative integration, complex analytical frameworks
- **User Profile**: Corporate strategy researcher studying market disruption
- **Key Testing**: Multi-source synthesis, sophisticated analysis protocols
- **Status**: Development needed

### TC006: Time-Sensitive Current Events

- **File**: `tc006_current_events.md`
- **Type**: Current Events Analysis
- **Complexity**: Intermediate
- **Focus**: Real-time information requirements, currency validation
- **User Profile**: Policy analyst researching recent regulatory changes
- **Key Testing**: Web search integration, rapid iteration protocols
- **Status**: Development needed

### TC007: Comparative Analysis Research

- **File**: `tc007_comparative_analysis.md`
- **Type**: Comparative Study
- **Complexity**: Advanced
- **Focus**: Cross-cultural analysis, systematic comparison frameworks
- **User Profile**: Public policy researcher comparing healthcare systems
- **Key Testing**: Multi-variable analysis, structured comparison protocols
- **Status**: Development needed

### TC008: Business Intelligence Research

- **File**: `tc008_business_intelligence.md`
- **Type**: Market Research
- **Complexity**: Intermediate
- **Focus**: Commercial source integration, competitive analysis
- **User Profile**: Startup founder researching competitive landscape
- **Key Testing**: Strategic insights, market analysis protocols
- **Status**: Development needed

### TC009: Technical/Scientific Deep Dive

- **File**: `tc009_technical_research.md`
- **Type**: Technical Literature Review
- **Complexity**: Advanced
- **Focus**: Specialized terminology, technical accuracy, expert-level analysis
- **User Profile**: R&D engineer researching battery technologies
- **Key Testing**: Domain expertise handling, technical validation protocols
- **Status**: Development needed

### TC010: Historical/Archival Research

- **File**: `tc010_historical_research.md`
- **Type**: Historical Analysis
- **Complexity**: Intermediate
- **Focus**: Primary and secondary source integration, chronological analysis
- **User Profile**: Historian researching social movements
- **Key Testing**: Historical source validation, archival research protocols
- **Status**: Development needed

### TC011: Single-Model Specialized Request

- **File**: `tc011_single_model.md`
- **Type**: Model-Specific Research
- **Complexity**: Intermediate
- **Focus**: Single-model workflows, targeted optimization
- **User Profile**: User wanting only Claude optimization for creative writing research
- **Key Testing**: Workflow flexibility, model-specific recommendations
- **Status**: Development needed

### TC012: Interdisciplinary Research

- **File**: `tc012_interdisciplinary.md`
- **Type**: Cross-Disciplinary Analysis
- **Complexity**: Advanced
- **Focus**: Multi-domain expertise, interdisciplinary synthesis
- **User Profile**: Researcher studying AI ethics, law, and psychology intersection
- **Key Testing**: Complex terminology management, domain integration
- **Status**: Development needed

## Test Case Development Standards

### Quality Requirements

Each test case must include:

#### Essential Components

- **Clear classification** (complexity, type, models)
- **Realistic user scenario** with specific context
- **Comprehensive test prompt** that bypasses socratic questioning
- **Expected outcomes** with measurable success criteria
- **Failure mode analysis** with specific performance benchmarks
- **Validation framework** with pre/post-test checklists

#### Success Criteria Framework

- **Process Evaluation**: Workflow efficiency, requirement capture
- **Prompt Quality**: Template adherence, clarity, model optimization
- **Research Design**: Methodology soundness, practical utility

#### Performance Benchmarks

- **Excellent** (Score: 5): Production-ready with optimal formatting and comprehensive methodology
- **Good** (Score: 4): Strong performance with 1-2 minor refinements needed
- **Satisfactory** (Score: 3): Meets basic requirements with some improvements needed
- **Needs Improvement** (Score: 2): Significant gaps requiring substantial work
- **Poor** (Score: 1): Major revision required before use

### Development Process

#### Phase 1: Design & Specification

1. **Identify testing gap** in current coverage
2. **Define user scenario** with realistic context
3. **Create comprehensive test prompt** with sufficient detail
4. **Establish success criteria** with measurable benchmarks
5. **Design failure mode analysis** with specific conditions

#### Phase 2: Validation & Refinement

1. **Execute trial run** with current system
2. **Analyze results** for test case effectiveness
3. **Refine specifications** based on trial outcomes
4. **Validate success criteria** for appropriate difficulty
5. **Document final test case** using standard template

#### Phase 3: Integration & Maintenance

1. **Add to test suite** with proper documentation
2. **Update roadmap** with completion status
3. **Establish maintenance schedule** for relevance
4. **Monitor performance** across system versions
5. **Refine based on feedback** from evaluations

## Testing Execution Protocol

### Pre-Test Setup

- [ ] Research Prompt Engineer system properly configured
- [ ] Current instructions and templates accessible
- [ ] Test case specifications reviewed
- [ ] Evaluation criteria understood
- [ ] Evaluator system prepared

### Test Execution

- [ ] Submit test prompt to Research Prompt Engineer
- [ ] Document complete interaction process
- [ ] Collect all generated research prompts
- [ ] Note any issues or unexpected behaviors
- [ ] Verify all artifacts are complete

### Evaluation Process

- [ ] Submit artifacts to Evaluator with test specification
- [ ] Provide system context (instruction and template paths)
- [ ] Specify evaluation focus areas
- [ ] Review comprehensive evaluation report
- [ ] Document scores and recommendations

### Post-Test Analysis

- [ ] Analyze scores and identify patterns
- [ ] Prioritize improvement recommendations
- [ ] Plan system refinements
- [ ] Update documentation

## Evaluation Metrics & Scoring

### Overall Scoring Framework

- **5 (Exceptional)**: Production-ready quality with optimal model-specific formatting, comprehensive research methodology, and robust quality assurance. Prompts can be used immediately without modification.
- **4 (High Quality)**: Strong performance with minor refinements needed. Good model optimization and sound research approach. 1-2 small improvements would make it excellent.
- **3 (Good/Satisfactory)**: Meets basic requirements with some improvements needed. Acceptable research design and reasonable model formatting. Functions adequately but has room for enhancement.
- **2 (Needs Improvement)**: Significant gaps present requiring substantial work. Instructions unclear in places, weak model optimization, or questionable research approach. Requires focused improvement effort.
- **1 (Poor/Inadequate)**: Major revision required before use. Critical information missing, incorrect formatting, flawed research design, or no quality assurance. Fundamental problems need addressing.

### Scoring Components

#### Template Adherence

**Score 5**: Perfect model-specific formatting, complete placeholder replacement, flawless structural compliance
**Score 4**: Minor formatting inconsistencies, 1-2 placeholder issues, generally proper structure
**Score 3**: Some template deviations, several placeholder problems, acceptable but improvable structure
**Score 2**: Significant formatting problems, multiple placeholder failures, poor structural compliance
**Score 1**: Major formatting failures, widespread placeholder errors, incorrect or missing structure

#### Research Methodology

**Score 5**: Sophisticated analytical frameworks, comprehensive source quality protocols, robust quality assurance
**Score 4**: Sound analytical approach with small gaps, good source protocols, adequate quality checks
**Score 3**: Basic analytical frameworks, reasonable source standards, minimum quality requirements met
**Score 2**: Weak analytical approaches, insufficient source standards, inadequate quality protocols
**Score 1**: Flawed or missing analytical frameworks, no source quality standards, absent quality assurance

#### Prompt Quality

**Score 5**: Crystal-clear instructions, optimal model-specific optimization, complete and actionable guidance
**Score 4**: Clear instructions with occasional ambiguity, good model optimization, mostly complete guidance
**Score 3**: Generally clear instructions with some confusion, adequate model optimization, acceptable completeness
**Score 2**: Unclear or confusing instructions, poor model optimization, incomplete guidance
**Score 1**: Incomprehensible instructions, no model optimization, critical information missing

### Key Performance Indicators

#### Process Efficiency

- **Interaction Length**: Minimal back-and-forth required
- **Requirement Capture**: Comprehensive detail gathering
- **Decision Points**: Clear, logical workflow progression
- **User Satisfaction**: Smooth, intuitive experience

#### Output Quality

- **Prompt Completeness**: All required sections present
- **Template Fidelity**: Proper model-specific formatting
- **Research Soundness**: Appropriate methodology and scope
- **Practical Utility**: Likely to produce valuable results

## Continuous Improvement Process

### Regular Testing Schedule

- **Weekly**: Execute priority test cases during active development
- **Bi-weekly**: Run comprehensive test suite
- **Monthly**: Develop new test cases for identified gaps
- **Quarterly**: Full system evaluation and benchmark review

### Improvement Integration Cycle

1. **Issue Identification**: Use test results to identify systematic problems
2. **Root Cause Analysis**: Determine underlying causes of performance issues
3. **Solution Development**: Create targeted improvements to instructions and templates
4. **Validation Testing**: Verify improvements through repeated testing
5. **Documentation Updates**: Maintain current system documentation

### Quality Assurance Protocols

- **Multiple Evaluators**: Use different evaluators to check consistency
- **Blind Testing**: Test without knowing expected outcomes
- **Regression Testing**: Ensure improvements don't break existing functionality
- **Performance Tracking**: Monitor improvement trends over time
- **Version Control**: Track all changes to test cases and results

## Contributing to the Testing Framework

### Adding New Test Cases

1. **Identify Coverage Gap**: Determine what scenarios aren't tested
2. **Use Standard Template**: Follow `test_case_template.md` structure
3. **Validate Design**: Ensure test case meets quality standards
4. **Execute Trial Run**: Test the test case for effectiveness
5. **Document Results**: Add to roadmap with proper status

### Improving Existing Test Cases

1. **Analyze Performance**: Review test case effectiveness over time
2. **Identify Refinements**: Determine needed improvements
3. **Update Specifications**: Enhance test case components
4. **Validate Changes**: Ensure improvements maintain test integrity
5. **Update Documentation**: Maintain current test case records

### Best Practices

- **Comprehensive Documentation**: Ensure all components are well-documented
- **Realistic Scenarios**: Base test cases on actual user needs
- **Measurable Outcomes**: Define clear success and failure criteria
- **Reproducible Results**: Enable consistent evaluation across runs
- **Actionable Insights**: Provide specific improvement guidance

## Troubleshooting

### Common Issues

**Inconsistent Evaluation Results**

- Verify evaluator configuration matches instructions
- Check for evaluator bias or misunderstanding
- Ensure test case specifications are clear and unambiguous

**Test Case Execution Problems**

- Confirm Research Prompt Engineer system is properly configured
- Verify all required files are accessible and current
- Check for version mismatches between instructions and templates

**Low-Quality Generated Prompts**

- Review test case requirements for realism and clarity
- Verify user prompts provide sufficient detail to bypass socratic questioning
- Check template and instruction alignment with user expectations

### Support Resources

- Review system documentation in parent directory
- Analyze successful test executions for patterns
- Consult evaluation reports for specific improvement guidance
- Reference existing test cases for proper structure examples

---

The Research Prompt Engineer Testing Framework provides a systematic approach to quality assurance and continuous improvement, ensuring the system maintains high standards while evolving to meet diverse user research needs across all supported AI platforms.
