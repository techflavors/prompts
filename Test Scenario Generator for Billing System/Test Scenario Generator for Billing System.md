# Test Scenario Generator for Billing System

You are a Quality Engineer expert specializing in comprehensive test planning for complex billing and metering systems.

## Input Sources
Before generating test scenarios, review and understand these key documentation sources:
- **System Overview**: https://docs.metronome.com/
- **Core Functionality**: https://docs.metronome.com/how-metronome-works/
- **Pay-as-you-go Implementation**: https://docs.metronome.com/launch-guides/pay-go/
- **Enterprise Use Cases**: https://docs.metronome.com/launch-guides/enterprise-commit/
- **Developer Resources**: https://docs.metronome.com/developer-resources/
- **API Documentation**: https://api.metronome.com/v1/docs/openapi

## Task
Generate a comprehensive CSV file containing detailed End-to-End test scenarios for a billing platform that handles:
- Pay-as-you-go pricing models
- Enterprise commitment-based billing
- Complex metering and aggregation
- Multi-tenant customer management
- Real-time billing calculations

## CSV Structure Required
Create a CSV with the following columns:

1. **Test Case ID** - Unique identifier (TC001, TC002, etc.)
2. **Feature Area/Use Case** - High-level feature being tested
3. **Key Coverage Areas** - Specific functionality within the feature
4. **Phase** - Testing phase (Setup, Execution, Validation, Cleanup)
5. **Test Case Summary** - Brief description of the test scenario
6. **Test Case Details** - Comprehensive step-by-step test instructions
7. **Additional Details** - Extra context, prerequisites, or special considerations
8. **Expected Result** - Detailed expected outcome for validation
9. **Comments** - Any additional notes or edge cases to consider

## Scope Requirements

### Core Features to Cover:
- Customer onboarding and configuration
- Pricing plan setup and management
- Metering data ingestion and processing
- Invoice generation and billing cycles
- Payment processing and reconciliation
- Reporting and analytics
- API integrations and webhooks
- Multi-currency and tax handling
- Commitment tracking and overage billing
- Real-time vs batch processing scenarios

### Test Types to Include:
- Positive flow testing
- Negative scenarios and error handling
- Edge cases and boundary conditions
- Performance and load scenarios
- Integration testing between components
- Data consistency and accuracy validation
- Security and access control testing
- Concurrent user scenarios

### Complexity Levels:
- Simple single-customer scenarios
- Multi-customer enterprise setups
- Complex pricing rule combinations
- High-volume transaction processing
- Cross-system integration scenarios

## Output Requirements
- Folder: "test scenario"
- Generate 400+ comprehensive test scenarios
- Ensure logical grouping by feature areas
- Include realistic business scenarios
- Cover both technical and functional testing
- Provide sufficient detail for automated test generation

## Quality Guidelines
- Each test case should be independent and executable
- Include proper test data requirements
- Specify clear validation criteria
- Consider real-world business scenarios
- Ensure comprehensive coverage across all billing workflows

Generate the CSV file with detailed, actionable test scenarios that cover the complete billing system functionality.