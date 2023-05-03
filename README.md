# Make Your Prediction App

Daml templates designed for a platform for making predictions of bitcoin price to get fact checked

## Overview

A signatory can create a BitcoinPricePrediction contract. BitcoinPricePrediction has a choice FactCheck that can be exercise by a specific controller. Upon marketMaker exercising the FactCheck choice, a BitcoinPriceFact contract is created.

## Workflow

To make prediction a gambler needs to create a Relationship contract with a marketMaker. Using this contract gambler can create BitcoinPricePrediction contracts.  
When BitcoinPricePrediction contract is created it can FackChecked by a marketMaker. As a result of a FackCheck a new BitcoinPriceFact is created.

## Building

To compile the project  
`daml build`

## Testing

To test all scripts: Either run the pre-written script in the Test.daml OR run:  
`daml test`

## Running

To load the project into the sandbox and start navigator:  
`daml start`