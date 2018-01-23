# Risk Allocation Extension

The risk allocation extension provides a way to describe the risk allocations defined in a contract.

Understanding the allocation of risk between the parties involved in a contracting process is important for comparison of the agreements between public authorities and private parties in different projects and jurisdictions.

This extension introduces a new `risk` building block and extends the `contract` section of OCDS block with a new `riskAllocation` field.

## Risk Allocation Field

The `contract/riskAllocation` field is an array of `risk` building blocks, describing the allocation of risks in the contract.

## Risk Building Block

The risk building block provides a way to:

* Categorize the risk against the [risk category codelist](http://standard.open-contracting.org/latest/en/schema/codelists/#risk-category)
* Provide a free text description of the risk
* Describe the allocation of the risk between the parties in the contracting process
* Describe the likelihood and fiscal impact of the risk
* Describe the mitigation for the risk
* Provide additional notes on the risk

```eval_rst
.. extensiontable::
   :extension: riskAllocation
```
