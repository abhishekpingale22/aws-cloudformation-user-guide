# AWS::WAFv2::RuleGroup OrStatementOne<a name="aws-properties-wafv2-rulegroup-orstatementone"></a>

Logical OR statement\.

## Syntax<a name="aws-properties-wafv2-rulegroup-orstatementone-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-wafv2-rulegroup-orstatementone-syntax.json"></a>

```
{
  "[Statements](#cfn-wafv2-rulegroup-orstatementone-statements)" : [StatementTwos](aws-properties-wafv2-rulegroup-statementtwos.md)
}
```

### YAML<a name="aws-properties-wafv2-rulegroup-orstatementone-syntax.yaml"></a>

```
  [Statements](#cfn-wafv2-rulegroup-orstatementone-statements): 
    [StatementTwos](aws-properties-wafv2-rulegroup-statementtwos.md)
```

## Properties<a name="aws-properties-wafv2-rulegroup-orstatementone-properties"></a>

`Statements`  <a name="cfn-wafv2-rulegroup-orstatementone-statements"></a>
Logical OR statements\.  
*Required*: No  
*Type*: [StatementTwos](aws-properties-wafv2-rulegroup-statementtwos.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)